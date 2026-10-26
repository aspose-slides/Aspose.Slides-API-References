---
title: CachedEnumerable()
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 1
url: /it/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) costruttore




```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | callback che viene chiamato quando è necessario il prossimo elemento. callback deve utilizzare il metodo Add per inserire il prossimo elemento o restituire false quando non ci sono più elementi |

## See Also

* Classe [Func](../../../system/func/)
* Classe [CachedEnumerable](../)
* Spazio dei nomi [System::Linq::Details](../../)
* Libreria [Aspose.Slides](../../../)