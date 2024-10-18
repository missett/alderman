---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
permalink: /
---

### Turn your network device configs into SQL data.
### Use standard SQL to find security problems, compliance breaches, and mis-configurations.
### Output your results into static HTML or CSV for easy reporting.
### Allow developers to create network automations and integrations without direct device access.

## Get Started For Free
```
docker run --rm -v `pwd`:/opt/data alderman upgrade      --database data.sql
docker run --rm -v `pwd`:/opt/data alderman data-upsert  --database data.sql \
    --input junos.cnf --dev-type juniper --dev-id alpha
docker run --rm -v `pwd`:/opt/data alderman workbook-gen --database data.sql
```

## Pricing

Start with up to two devices and access all features for free, forever. 

When you decide you like what you see, add more devices with a paid subscription.

£5 per month, per device. Simple.

Change your subscription at any time to add more or less devices. Pay for one month or twenty months. 
