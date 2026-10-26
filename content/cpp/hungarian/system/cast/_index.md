---
title: Cast()
second_title: Aspose.Slides C++ API Referencia
description: Átalakítást hajt végre SmartPtr objektumokon.
type: docs
weight: 2510
url: /hu/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) függvény


Átalakítást hajt végre a [SmartPtr](../smartptr/) objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél mutatott típus. |
| TFrom | Forrás mutatott típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Forrás mutató. |

### Visszatérési érték

Az átalakítás eredménye, ha az átalakítás engedélyezett.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Struktúra [IsExceptionWrapper](../isexceptionwrapper/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)