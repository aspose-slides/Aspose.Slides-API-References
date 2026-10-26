---
title: Cast()
second_title: Aspose.Slides för C++ API-referens
description: Utför cast på SmartPtr-objekt.
type: docs
weight: 2510
url: /sv/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) funktion


Utför cast på [SmartPtr](../smartptr/) objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
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

Cast-resultat om cast är tillåtet.

## Se även

* Klass [SmartPtr](../smartptr/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)