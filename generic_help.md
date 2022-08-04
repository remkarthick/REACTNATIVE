# GIT
## To Configure the  email and name

```
git config --global user.email "email@emailserver.com"
git config --global user.name "My Full Name"
```
## To Check the configured email and name

```
git config --global user.email
OP: <mail_id>@<domain>
git config --global user.name 
OP: <First Name> <Last Name>
```
## To Check current Proxy
```
git config --get-regexp http.*proxy
```
## To Remove Proxy
```
git config --global --unset http.proxy
```

## To Validate if proxy is removed
```
git config --global --get http.proxy
```

## To Set a new Proxy
```
git config --global http.proxy http://proxyUsername:proxyPassword@proxy.server.com:port
```


## Add Remote from Github
View  -> Command Palette -> type "Git: Add Remote"

# Android
## Location of Android AVD after android studio is installed
```
C:\Users\<user>\AppData\Local\Android\Sdk\emulator
```

## To Find the AVD names in your system
````emulator.exe -list-avds```

## Type the below command to open the AVD
```emulator.exe -avd "Pixel_5_API_33"```


..