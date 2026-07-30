---
title: get_IsDecorative()
second_title: Aspose.Slides pro C++ API Reference
description: Získá možnost 'Označit jako dekorativní' čtení/zápisu bool.
type: docs
weight: 404
url: /cs/aspose.slides/ishape/get_isdecorative/
---
## IShape::get_IsDecorative() metoda


Vrací možnost 'Označit jako dekorativní' čtení/zápisu **bool**.

```cpp
virtual bool Aspose::Slides::IShape::get_IsDecorative()=0
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Viz také

* Třída [IShape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)