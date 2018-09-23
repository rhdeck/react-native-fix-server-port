# react-native-fix-server-port
Package can change the port being used by the dev server. 

This removes a manual step if app being worked on is meant to be used on a different port than 8081. Which if rm -rf node_modules is executed a lot can save some time.

Notes:
1. iOS only
2. New port is saved to package.json
3. Enter 'yarn rnsp' to start react-native server with the new port

TODO:
This is a dirty method that changes the files I know x-ante are required for port change to work. Need to look at how dev server spins up so I can write more intelligent code