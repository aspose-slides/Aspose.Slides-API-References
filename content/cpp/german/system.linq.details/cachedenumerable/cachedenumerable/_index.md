---
title: CachedEnumerable()
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 1
url: /de/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) constructor

```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | Callback, das aufgerufen wird, wenn das nächste Element benötigt wird. Der Callback sollte die Add-Methode verwenden, um das nächste Element einzufügen, und false zurückgeben, wenn keine weiteren Elemente mehr vorhanden sind. |

## Siehe auch

* Class [Func](../../../system/func/)
* Class [CachedEnumerable](../)
* Namespace [System::Linq::Details](../../)
* Library [Aspose.Slides](../../../)