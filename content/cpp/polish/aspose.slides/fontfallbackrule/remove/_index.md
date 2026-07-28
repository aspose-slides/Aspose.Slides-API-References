---
title: Remove()
second_title: Aspose.Slides dla C++ – Referencja API
description: Usuwa pierwsze wystąpienie określonej czcionki FallBack z listy.
type: docs
weight: 118
url: /pl/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) metoda


Usuwa pierwsze wystąpienie określonej czcionki FallBack z listy.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nazwa czcionki do usunięcia z listy. |
## Uwagi



```cpp
// Utwórz regułę zawierającą listę czcionek.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Usuń Tahoma z listy.
newRule->Remove(u"Tahoma");
```


## Zobacz również

* Klasa [String](../../../system/string/)
* Klasa [FontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)