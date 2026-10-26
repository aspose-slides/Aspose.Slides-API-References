---
title: get_NoBreak()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Bez přerušení Tato vlastnost určuje \"nepřerušitelnou\" vlastnost na objektovém boxu. Když je true, žádná zalomení řádku nemohou nastat uvnitř boxu. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když tento prvek není specifikován, mohou se uvnitř boxu vyskytnout zalomení řádku. Výchozí: true"
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() metoda

Bez přerušení Tato vlastnost určuje \"nepřerušitelný\" vlastnost na objektovém boxu. Když je true, žádná zalomení řádku nemohou nastat uvnitř boxu. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když tento prvek není specifikován, mohou se uvnitř boxu vyskytnout zalomení řádku. Výchozí: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Poznámky


Příklad: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Viz také

* Třída [MathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)