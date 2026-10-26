---
title: ForceStaticCast()
second_title: Aspose.Slides C++ API referencia
description: Valós statikus átkonvertálást hajt végre a SmartPtr objektumokon.
type: docs
weight: 2588
url: /hu/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) függvény

Valós statikus átkonvertálást hajt végre a [SmartPtr](../smartptr/) objektumokon.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél mutató típus. |
| TFrom | Forrás mutató típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Forrás mutató. |

### Visszatérési érték

Az átkonvertálás eredménye, ha az átkonvertálás engedélyezett, egyébként a viselkedés meghatározatlan.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Struktúra [CastResult](../castresult/)
* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)