# Overview

Forked from https://github.com/jpmens/check-mqtt, use it for main package information

# Extra Configuration

  -T <transport>, --transport <transport>
                        connection protocol (default: tcp)


# Examples

## Connect with tcp 

```
./check-mqtt.py -H localhost -P 1883 -u user -m 10

OK - message from nagios/test at localhost in 0.73s | response_time=0.73 value=PiNG
```

## Connect with ws 

```
./check-mqtt.py -H localhost -P 8083 -u user -m 10 -T websockets

OK - message from nagios/test at localhost in 0.76s | response_time=0.76 value=PiNG
```