### pid name space

## compile pid.c
```
# gcc -o pid pid.c
```

## get pid of container
```
# ps aux|grep pid
```

## enter pid name space of container
```
# nsenter -t $child_pid -m /bin/sh
```

## get pid in container name space
```
# ps 
```
