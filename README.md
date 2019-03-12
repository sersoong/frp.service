# frp.service
frp service for systemd

### How to use?

```
git clone https://github.com/sersoong/frp.service.git
cd frp.service
```

**Edit the frps.service or frpc.service file. Replace all \* with your setting value in the file.**

**And copy them to `/lib/systemd/system/`.**
```
#sudo cp frps.service /lib/systemd/system/
or
#sudo cp frpc.service /lib/systemd/system/
```

**Then Run**
```
#sudo systemctl start frps
#sudo systemctl enable frps
or
#sudo systemctl start frpc
#sudo systemctl enable frpc
```
**Or Stop with**
```
#sudo systemctl stop frps
or
#sudo systemctl stop frpc
```
