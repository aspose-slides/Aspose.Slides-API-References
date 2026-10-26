---
title: ForceStaticCast()
second_title: Aspose.Slides för C++ API-referens
description: Utför en verklig statisk cast på SmartPtr-objekt.
type: docs
weight: 2588
url: /sv/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) funktion

Utför en verklig statisk kastning på [SmartPtr](../smartptr/) objekt.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointerns typ. |
| TFrom | Källpointerns typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet, annars är beteendet odefinierat.

## Se även

* Klass [SmartPtr](../smartptr/)
* Struktur [CastResult](../castresult/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)