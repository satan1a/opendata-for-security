# CNAME Record

## Overview

This dataset contains responses to DNS requests for all domains of the ICANN Centralized Zone Data Service (CZDS). The provided data is a ZIP archive containing the name, type, value and timestamp of any returned record of the given name in JSON format.

⚠️The file compression ratio is about 10~15, that is, the 2GB compressed file may be as high as 20~30GB after decompression, please pay attention to your hard disk space:-P

The following are examples of data formats:

```json
{"name":"engineered.agency.","type":"CNAME","class":"IN","status":"NOERROR","rx_ts":1663753959668765317,"data":{"authorities":[{"ttl":300,"type":"SOA","class":"IN","name":"engineered.agency.","data":"ns-cloud-e1.googledomains.com. cloud-dns-hostmaster.google.com. 2 21600 3600 259200 300"}]},"flags":["rd","ra"],"resolver":"141.1.1.1:53"}
{"name":"founders.agency.","type":"CNAME","class":"IN","status":"NOERROR","rx_ts":1663753959669301263,"data":{"authorities":[{"ttl":600,"type":"SOA","class":"IN","name":"founders.agency.","data":"ns53.domaincontrol.com. dns.jomax.net. 2020070900 28800 7200 604800 600"}]},"flags":["rd","ra"],"resolver":"62.149.128.2:53"}
{"name":"edito.agency.","type":"CNAME","class":"IN","status":"NOERROR","rx_ts":1663753959669326708,"data":{"authorities":[{"ttl":60,"type":"SOA","class":"IN","name":"edito.agency.","data":"dns14.ovh.net. tech.ovh.net. 2022090201 86400 3600 3600000 60"}]},"flags":["rd","ra"],"resolver":"209.216.160.131:53"}
```



## Dataset Listing

| File Name                                                    | Size    | Updated At |
| ------------------------------------------------------------ | ------- | ---------- |
| [2022-09-08-06-fdns_cname.json.zip](https://fdns.sgp1.vultrobjects.com/2022-09-08-06-fdns_cname.json.zip) | 1.90 GB | 2022-09-08 |
| [2022-09-14-17-fdns_cname.json.zip](https://fdns.sgp1.vultrobjects.com/2022-09-14-17-fdns_cname.json.zip) | 2.14 GB | 2022-09-14 |
| [2022-09-15-17-fdns_cname.json.zip](https://fdns.sgp1.vultrobjects.com/2022-09-15-17-fdns_cname.json.zip) | 2.15 GB | 2022-09-15 |
| [2022-09-16-17-fdns_cname.json.zip](https://fdns.sgp1.vultrobjects.com/2022-09-16-17-fdns_cname.json.zip) | 2.15 GB | 2022-09-16 |
| [2022-09-17-17-fdns_cname.json.zip](https://fdns.sgp1.vultrobjects.com/2022-09-17-17-fdns_cname.json.zip) | 2.18 GB | 2022-09-17 |
| [2022-09-18-17-fdns_cname.json.zip](https://fdns.sgp1.vultrobjects.com/2022-09-18-17-fdns_cname.json.zip) | 2.20 GB | 2022-09-18 |
| [2022-09-19-17-fdns_cname.json.zip](https://fdns.sgp1.vultrobjects.com/2022-09-19-17-fdns_cname.json.zip) | 2.15 GB | 2022-09-19 |
| [2022-09-20-17-fdns_cname.json.zip](https://fdns.sgp1.vultrobjects.com/2022-09-20-17-fdns_cname.json.zip) | 1.95 GB | 2022-09-20 |