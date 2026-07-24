---
title: HttpCacheAgeControl
second_title: Aspose.Slides für C++ API-Referenz
description: CacheAgeControl wird verwendet, um Präferenzen in Bezug auf das Alter und die Frische von zwischengespeicherten Elementen anzugeben.
type: docs
weight: 53
url: /de/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum


CacheAgeControl wird verwendet, um Präferenzen in Bezug auf das Alter und die Frische von zwischengespeicherten Elementen anzugeben.

```cpp
enum class HttpCacheAgeControl
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Nur für den internen Gebrauch. |
| MinFresh | 1 | Der Inhalt kann aus dem Cache entnommen werden, wenn die verbleibende Zeit bis zum Ablauf größer oder gleich der mit diesem Wert angegebenen Zeit ist. |
| MaxAge | 2 | Der Inhalt kann aus dem Cache entnommen werden, bis er älter ist als das mit diesem Wert angegebene Alter. |
| MaxStale | 4 | Der Inhalt kann aus dem Cache entnommen werden, nachdem er abgelaufen ist, bis die mit diesem Wert angegebene Zeit verstrichen ist. |
| MaxAgeAndMinFresh | 3 | MaxAge und MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge und MaxStale. |

## Siehe auch

* Namensraum [System::Net::Cache](../)
* Bibliothek [Aspose.Slides](../../)