---
title: RemoveAt()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraňuje písmo FallBack na určeném indexu v seznamu.
type: docs
weight: 92
url: /cs/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) metoda


Odstraňuje písmo FallBack na určeném indexu v seznamu.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index písma, který má být odstraněn. |
## Poznámky



```cpp
// Vytvořte pravidlo, které obsahuje seznam písem.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Odstranění Tahoma ze seznamu
newRule->RemoveAt(2);
```


## Viz také

* Třída [IFontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)