---
title: Remove()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraní první výskyt konkrétního fontu FallBack ze seznamu.
type: docs
weight: 79
url: /cs/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) metoda

Odstraní první výskyt konkrétního fontu FallBack ze seznamu.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Název fontu, který má být odstraněn ze seznamu. |
## Poznámky

```cpp
// Vytvoří pravidlo, které obsahuje seznam písem.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Odstranění Tahoma ze seznamu
newRule->Remove(u"Tahoma");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [IFontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)