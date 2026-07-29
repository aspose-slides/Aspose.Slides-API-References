---
title: ConstCast()
second_title: Aspose.Slides för C++ API-referens
description: Slut på föråldrade kast.
type: docs
weight: 2575
url: /sv/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) funktion


Slut på föråldrade kast.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Typ för mål-pekare. |
| TFrom | Typ för källa-pekare. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet eller nullptr annars.

## Anmärkningar


Utför const-cast på [SmartPtr](../smartptr/)-objekt. 
## Se även

* Klass [SmartPtr](../smartptr/)
* Struktur [CastResult](../castresult/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)