---
title: ForceStaticCast()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Provádí skutečný statický převod na objektech SmartPtr.
type: docs
weight: 2588
url: /cs/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const&) funkce

Provádí skutečný statický převod na objektech [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ ukazatele. |
| TFrom | Zdrojový typ ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Zdrojový ukazatel. |

### Návratová hodnota

Výsledek převodu, pokud je převod povolen, jinak je chování nedefinováno.

## Viz také

* Třída [SmartPtr](../smartptr/)
* Struktura [CastResult](../castresult/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)