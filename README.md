# nf.io
### A File System Abstraction for NFV Orchestration

### Installation Instructions

* Install [fuse](http://fuse.sourceforge.net/) >= 2.6 
* Add your username to the group fuse `sudo addgroup <username> fuse`
* Logout and login again to update user group

### To Run

```bash
  mkdir /vnfsroot
  mkdir -p /vnfsroot/nf-types/fw
  mkdir -p /vnfsroot/nf-types/proxy
  mkdir -p /vnfsroot/nf-types/ids
  mkdir -p /vnfsroot/chns
  chown -R <username>:<username> /vnfsroot
  mkdir /nfio
  chown <username>:<username> /vnfsroot
  python nfio.py /vnfsroot /nfio
```

An online demonstration is available at http://faizulbari.github.io/nf.io/