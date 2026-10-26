---
title: ConstCast()
second_title: Aspose.Slides pro referenční dokumentaci API C++
description: Konec zastaralých přetypování.
type: docs
weight: 2575
url: /cs/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) funkce


Konec zastaralých přetypování.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ ukazovaného objektu. |
| TFrom | Zdrojový typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Zdrojový ukazatel. |

### Návratová hodnota

Výsledek přetypování, pokud je přetypování povoleno, nebo nullptr jinak.
## Poznámky


Provádí const přetypování na objektech [SmartPtr](../smartptr/). 
## Viz také

* Třída [SmartPtr](../smartptr/)
* Struktura [CastResult](../castresult/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)