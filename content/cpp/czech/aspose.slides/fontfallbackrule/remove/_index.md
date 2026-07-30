---
title: Remove()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Odstraňuje první výskyt konkrétního fontu FallBack ze seznamu.
type: docs
weight: 118
url: /cs/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) metoda

Odstraňuje první výskyt konkrétního fontu FallBack ze seznamu.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Název fontu, který se má odstranit ze seznamu. |
## Poznámky



```cpp
// Vytvoří pravidlo obsahující seznam fontů.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Odstraní Tahoma ze seznamu.
newRule->Remove(u"Tahoma");
```


## Viz také

* Třída [String](../../../system/string/)
* Třída [FontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)