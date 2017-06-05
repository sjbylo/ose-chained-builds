# Example Go builder using a build chain

## Thanks to Jorge's examples at https://blog.openshift.com/chaining-builds/ 

Execute the example.sh script or manually execute the commands inside to see how it works.

```
bash example.sh
```

Run the following in 2 different windows to view both the build in the chain

```
while true; do clear; oc logs bc/builder -f; sleep 2; done
while true; do clear; oc logs bc/runtime -f; sleep 2; done
```

