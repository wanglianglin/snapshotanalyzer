# snapshotanalyzer
Demo project to manage AWS EC2 instance snapshots.

## About
This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configure
Shotty uses the configuration file created by the AWS cli.

e.g.
`aws configure --profile shotty`

## Running
This project requires Python 3 and the requests package.
First, install pipenv. Then:

```
pipenv install
pipenv run python shotty/shotty.py <command> <subcommand> [--project=PROJECT]
```
+ *command* is instances, volumes, or snapshots
+ *subcommand* is snapshot, list, start, or stop_instances
+ *project* is optional
