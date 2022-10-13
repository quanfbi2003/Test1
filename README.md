apktool if 
apktool d  -r -s
apktool b 
java -jar apksigner.jar -a  --out Signed


reflutter
mv release.RE.apk .apk
java -jar apksigner.jar --apk  --out Signed
