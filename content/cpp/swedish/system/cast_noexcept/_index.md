---
title: Cast_noexcept()
second_title: Aspose.Slides för C++ API-referens
description: Utför cast på SmartPtr-objekt.
type: docs
weight: 2497
url: /sv/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) funktion

Utför cast på [SmartPtr](../smartptr/) objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |
| TFrom | Källpointee-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Källpekare. |

### Returvärde

Castresultat om kastet är tillåtet eller nullptr annars.

## Se även

* Klass [SmartPtr](../smartptr/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)