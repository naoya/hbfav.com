hbfav.com DNS records
=====================

This repository contains Route 53 DNS records for hbfav.com.

Scribbled memo
--------------

### Export settings from Route53

```
% bundle exec roadwork -e -o Routefile
```

### Apply changes

Dry-Run

```
% bundle exec roadwork -a --dry-run
```

### Do test

```
% bundle exec roadwork -t
```

See Also
--------

[Roadworker](https://bitbucket.org/winebarrel/roadworker)
