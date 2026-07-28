---
title: "System::Net::Cache"
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 664
url: /hu/system.net.cache/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | HTTP gyorsítótár szabály, amely kifejezi az RFC2616 HTTP gyorsítótárazási szemantikai. Az osztály példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek. |
| [RequestCachePolicy](./requestcachepolicy/) | Általános kérés gyorsítótár szabály, amelyet a [Http](../system.net.http/), FTP stb. gyorsítótárazására használnak. Az osztály példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek. |
## Enumerációk

| Enumeráció | Leírás |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | Az enumeráció leírja a gyorsítótár beállításait, amelyek bármely [WebRequest](../system.net/webrequest/)-re vonatkoznak. |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | Az enumeráció leírja a HTTP gyorsítótár beállításait. |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | A CacheAgeControl-t a gyorsítótárazott elem korával és frissességével kapcsolatos preferenciák meghatározására használják. |