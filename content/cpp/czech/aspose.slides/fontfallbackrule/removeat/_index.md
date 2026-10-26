---
title: RemoveAt()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraní písmo FallBack na určeném indexu seznamu.
type: docs
weight: 131
url: /cs/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) metoda


Odstraní písmo FallBack na určeném indexu seznamu.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index začínající nulou písma, které se má odstranit. |
## Poznámky



```cpp
// Vytvoří pravidlo, které obsahuje seznam písem.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Odstraní Tahoma ze seznamu.
newRule->RemoveAt(2);
```


## Viz také

* Třída [FontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)