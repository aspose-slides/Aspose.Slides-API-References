---
title: get_NoBreak()
second_title: Aspose.Slides pro C++ API Reference
description: "Žádné zalomení. Tato vlastnost určuje vlastnost \"unbreakable\" na objektovém boxu. Když je true, v rámci boxu nemohou nastat žádná zalomení řádků. To může být důležité pro emulátory operátorů, kteří se skládají z více než jednoho binárního operátoru. Když není tento prvek specifikován, mohou se v boxu objevit zalomení. Výchozí: true"
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() metoda

Žádné zalomení. Tato vlastnost určuje vlastnost \"unbreakable\" na objektovém boxu. Když je true, nelze v rámci boxu provádět žádné zalomení řádků. To může být důležité pro emulátory operátorů, kteří se skládají z více než jednoho binárního operátoru. Když není tento prvek specifikován, mohou se v boxu objevit zalomení. Výchozí: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
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