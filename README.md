# pg-dev
A lightweight script that helps you setup, start/stop and remove a Postgres development server.

### Requirements
Requires [Docker](https://www.docker.com) to be installed on your machine.

### Available commands
|Command|Description|
|-------|-----------|
|setup  |Will pull the latest Postgres image from Docker.<br/>If you don't have the image already, you have to run this command first.|
|psql   |Run psql command.<br/>If you don't want to use the default instance, use this command followed by a name of the instance.<br/>**Example**: pg-dev psql [name of instance]|
|start  |Start a new instance of Postgres.<br/>If you don't want to use the default instance, use this command followed by a name of the instance.<br/>**Example**: pg-dev start [name of instance]|
|status |Show status of a Postgres instance.<br/>If you don't want to use the default instance, use this command followed by a name of the instance.<br/>**Example**: pg-dev status [name of instance]|
|stop   |Stop a Postgres instance.<br/>If you don't want to use the default instance, use this command followed by a name of the instance.<br/>**Example**: pg-dev status [name of instance]|
|volume |List existing volumes.|
|remove |Remove a Postgres instance.<br/>If you don't want to use the default instance, use this command followed by a name of the instance.<br/>**NOTE**: To remove the instance you will be asked to<br/>enter the name of instance to perform the removal.<br/>**Example**: pg-dev remove [name of instance]|