---
title: Remove()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Usuwa pierwsze wystąpienie określonej czcionki FallBack z listy.
type: docs
weight: 79
url: /pl/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) metoda


Usuwa pierwsze wystąpienie określonej czcionki FallBack z listy.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | nazwa czcionki do usunięcia z listy. |
## Uwagi



```cpp
// Utwórz regułę, która zawiera listę czcionek.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Usuwanie Tahoma z listy
newRule->Remove(u"Tahoma");
```


## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IFontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)