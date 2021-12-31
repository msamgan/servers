# Commands

Below are all the available commands.

## list

To list all the available commands

```shell
sh run list
```

## servers

To run all the added service in the system all at ones.

```shell
sh run servers
```

## check

To check the running servers status

```shell
sh run check
```

## kill

To kill all the running servers

```shell
sh run kill
```

To kill a particular service

```shell
sh run kill <service_name>
```

## service

service have all the commands related to service starting with

### list

To get the list of all the added services

```shell
ah run service list
```

### add

To add a new service to system

```shell
sh run service add
```

### remove

To remove a service (service name is required)

```shell
sh run service remove <service_name>
```

### start

To run the server for a particular service (service name is required)

```shell
sh run service start <service_name>
```
