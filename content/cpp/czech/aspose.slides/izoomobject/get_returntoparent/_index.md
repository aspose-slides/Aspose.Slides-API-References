---
title: get_ReturnToParent()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Získá chování navigace v prezentaci. Čte bool. Výchozí hodnota: false"
type: docs
weight: 27
url: /cs/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() metoda


Získá chování navigace v prezentaci. Čte **bool**. Výchozí hodnota: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Poznámky


Hodnota true vlastnosti určuje chování navigace návratu k rodiči v prezentaci. 

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