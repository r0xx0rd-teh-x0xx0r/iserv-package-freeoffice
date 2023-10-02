# iserv-package-freeoffice

### Installation auf dem iServ Server:

#### Voraussetzungen: 
-  root Zugriff auf dem iServ Server
-  Git und git-lfs (git large file) müssen installiert sein, falls das nicht der Fall ist, müssen die Packete wie volg installiert werden:

```
apt-get install git git-lfs
```

#### In das Zielverzeichnis wechseln:

```
cd /srv/deploy/install/
```


#### Git-repository klonen:

```
git clone https://github.com/r0xx0rd-teh-x0xx0r/iserv-package-freeoffice.git onlyoffice
```

#### In das Verzeichnis gehen und die msi-datei mit git-lfs herunterladen:
```
cd freeoffice
git lfs pull
```

#### iServ Deployment-Dienst über änderungen informieren:
```
chkdeploy
```
