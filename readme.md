To update image:

```
cd testapp/dev
kustomize edit set image nginx=nginx:${VERSION}
git add kustomization.yml
git commit -m "version updated"
git push
```