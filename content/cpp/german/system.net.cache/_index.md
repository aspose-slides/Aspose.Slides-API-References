---
title: "System::Net::Cache"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 664
url: /de/system.net.cache/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | HTTP-Cache-Richtlinie, die die RFC2616 HTTP-Cache-Semantik ausdrückt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [RequestCachePolicy](./requestcachepolicy/) | Allgemeine Anforderungs-Cache-Richtlinie, die für das Caching von [Http](../system.net.http/), FTP usw. verwendet wird. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | Die Aufzählung beschreibt die Cache-Einstellungen, die für jedes [WebRequest](../system.net/webrequest/) gelten. |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | Die Aufzählung beschreibt die Cache-Einstellungen für HTTP. |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | CacheAgeControl wird verwendet, um Präferenzen in Bezug auf das Alter und die Frische von zwischengespeicherten Elementen festzulegen. |