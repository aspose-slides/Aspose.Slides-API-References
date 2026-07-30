---
title: Cast_noexcept()
second_title: Aspose.Slides pro C++ referenci API
description: Provádí přetypování na objektech SmartPtr.
type: docs
weight: 2497
url: /cs/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) funkce

Provádí přetypování na objektech [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ ukazovaného objektu. |
| TFrom | Zdrojový typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Ukazatel na zdroj. |

### Návratová hodnota

Výsledek přetypování, pokud je přetypování povoleno, nebo nullptr jinak.

## Viz také

* Třída [SmartPtr](../smartptr/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)