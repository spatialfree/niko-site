

```shell
# publish
rsync -avz --exclude-from='no_sync.txt' --progress ~/dofdev/niko-site/ root@cloudred:/var/www/niko-site/
```