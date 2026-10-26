---
title: set_NoBreak()
second_title: Aspose.Slides pro C++ API Reference
description: "Žádné zalomení Tato vlastnost určuje vlastnost \"nepřerušený\" na objektovém boxu. Když je true, v rámci boxu nemohou nastat žádná zalomení řádku. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když tento prvek není specifikován, mohou v boxu nastat zalomení. Výchozí hodnota: true"
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) metoda

Žádné zalomení Tato vlastnost určuje vlastnost "nepřerušený" na objektovém boxu. Když je true, v rámci boxu nemohou vzniknout žádné zalomení řádku. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když není tento prvek specifikován, mohou se v boxu objevit zalomení. Výchozí hodnota: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
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