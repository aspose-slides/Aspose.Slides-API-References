---
title: get_IsDecorative()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá volbu 'Mark as decorative' číst/zapisovat bool.
type: docs
weight: 521
url: /cs/aspose.slides/shape/get_isdecorative/
---
## Shape::get_IsDecorative() metoda


Získá volbu 'Označit jako dekorativní' číst/zapisovat **bool**.

```cpp
bool Aspose::Slides::Shape::get_IsDecorative() override
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Viz také

* Třída [Shape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)