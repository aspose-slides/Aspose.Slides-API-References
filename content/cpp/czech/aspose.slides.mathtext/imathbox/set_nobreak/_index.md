---
title: set_NoBreak()
second_title: Reference API Aspose.Slides pro C++
description: "Bez zalomení. Tato vlastnost určuje vlastnost \"unbreakable\" u objektového boxu. Když je true, v boxu nemohou nastat žádná zalomení řádků. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když tento prvek není specifikován, mohou se v boxu vyskytovat zalomení. Výchozí: true"
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) metoda


Bez zalomení. Tato vlastnost určuje vlastnost \"unbreakable\" u objektového boxu. Když je true, v rámci boxu nemohou nastat žádné zalomení řádku. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když tento prvek není specifikován, mohou se v boxu vyskytovat zalomení. Výchozí: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Poznámky


Příklad:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Viz také

* Třída [IMathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)