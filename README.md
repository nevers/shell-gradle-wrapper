# shell-gradle-wrapper

A simple shell script for running the gradle wrapper at any folder of your project without having to specifying the full path.

For example:
```
project/some/sub/sub/sub/dir$ ../../../../../gradlew tasks # this script avoids this mess...
project/some/sub/sub/sub/dir$ gw task # ...and allows a short and simple notation
```

Installation:

```
bash <(curl -s https://raw.githubusercontent.com/nevers/shell-gradle-wrapper/master/install-gradle-wrapper)
```
