---
title: Cast()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Provádí přetypování objektů SmartPtr.
type: docs
weight: 2510
url: /cs/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) function

Provádí přetypování na objektech [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
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

Výsledek přetypování, pokud je přetypování povoleno.

## Viz také

* Třída [SmartPtr](../smartptr/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)