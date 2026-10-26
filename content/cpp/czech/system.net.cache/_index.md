---
title: "System::Net::Cache"
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 664
url: /cs/system.net.cache/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | Politika mezipaměti HTTP, která vyjadřuje sémantiku cachování podle RFC2616. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to způsobí chyby za běhu a/nebo selhání aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [RequestCachePolicy](./requestcachepolicy/) | Obecná politika cachování požadavků používaná pro ukládání do mezipaměti [Http](../system.net.http/), FTP atd. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to způsobí chyby za běhu a/nebo selhání aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |

## Výčty

| Výčet | Popis |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | Výčet popisuje nastavení mezipaměti použitelné pro libovolný [WebRequest](../system.net/webrequest/). |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | Výčet popisuje nastavení mezipaměti pro HTTP. |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | CacheAgeControl se používá k určení preferencí ohledně stáří a čerstvosti položky v mezipaměti. |