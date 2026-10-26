---
title: "System::Net::Cache"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 664
url: /sv/system.net.cache/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | HTTP-cachepolicy som uttrycker RFC2616 HTTP-cache semantiska objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körtidsfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [RequestCachePolicy](./requestcachepolicy/) | Gemensam begärancachepolicy som används för cachning av [Http](../system.net.http/), FTP osv. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körtidsfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |

## Enumeratorer

| Enum | Beskrivning |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | Enum beskriver cacheinställningar som gäller för alla [WebRequest](../system.net/webrequest/). |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | Enum beskriver cacheinställningar för HTTP. |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | CacheAgeControl används för att ange preferenser med avseende på cachat objekts ålder och fräschhet. |