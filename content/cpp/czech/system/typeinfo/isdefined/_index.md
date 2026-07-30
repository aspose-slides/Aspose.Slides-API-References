---
title: IsDefined()
second_title: Aspose.Slides pro C++ referenční příručka API
description: NEIMPLEMENTOVÁNO. Udává, zda je na tento člen aplikován jeden nebo více atributů specifikovaného typu nebo jeho odvozených typů.
type: docs
weight: 157
url: /cs/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const metoda


NENÍ IMPLEMENTOVÁNO. Indikuje, zda je na tento člen aplikován jeden nebo více atributů specifikovaného typu nebo jeho odvozených typů.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Typ vlastního atributu, který se má hledat. Vyhledávání zahrnuje odvozené typy. |
| inherit | **bool** | true, pokud se má prohledat řetězec dědičnosti tohoto členu za účelem nalezení atributů; jinak false. Tento parametr se ignoruje pro vlastnosti a události. |

### Návratová hodnota

true, pokud je na tento člen aplikována jedna nebo více instancí attributeType nebo některý z jeho odvozených typů; jinak false.

## Viz také

* Třída [TypeInfo](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)