---
title: CachedEnumerable()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 1
url: /sv/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) konstruktor




```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | återuppringningsfunktion som anropas när nästa objekt behövs. återuppringningsfunktionen bör använda Add-metoden för att infoga nästa objekt eller returnera false när inga fler objekt finns |

## Se även

* Klass [Func](../../../system/func/)
* Klass [CachedEnumerable](../)
* Namnrymd [System::Linq::Details](../../)
* Bibliotek [Aspose.Slides](../../../)