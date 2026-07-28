---
title: Cast_noexcept()
second_title: Aspose.Slides a C++ API-referencia
description: Átalakítást hajt végre SmartPtr objektumokon.
type: docs
weight: 2497
url: /hu/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) függvény

Átalakítást hajt végre a [SmartPtr](../smartptr/) objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél mutatott típus. |
| TFrom | Forrás mutatott típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Forrás mutató. |

### Visszatérési érték

Az átkonvertálás eredménye, ha engedélyezett, egyébként nullptr.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Struktúra [IsExceptionWrapper](../isexceptionwrapper/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)