# Execute npm command

```
docker run -e "NODE_ENV=production" -u "node" -m "300M" --memory-swap "1G" -w "/home/node/app" node npm -v
```

# Check and fix duplicate package in bundle file

Using this plugin to check duplicate package:
https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin

Check that package readme to know how to resole duplicate packages.