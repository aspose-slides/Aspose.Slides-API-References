---
title: set_ReturnToParent()
second_title: Aspose.Slides pro C++ API Referenci
description: "Nastavuje chování navigace v prezentaci. Zapište bool. Výchozí hodnota: false"
type: docs
weight: 40
url: /cs/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) metoda


Nastavuje chování navigace v prezentaci. Zapište **bool**. Výchozí hodnota: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Poznámky


Hodnota true vlastnosti určuje chování návratu k nadřazenému prvku v prezentaci. 

Příklad: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Viz také

* Třída [IZoomObject](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)