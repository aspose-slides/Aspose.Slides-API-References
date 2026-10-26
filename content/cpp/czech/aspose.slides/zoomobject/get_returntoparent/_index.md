---
title: get_ReturnToParent()
second_title: Aspose.Slides pro C++ referenci API
description: "Získá chování navigace v prezentaci. Čte bool. Výchozí hodnota: false"
type: docs
weight: 27
url: /cs/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() metoda


Získá chování navigace v prezentaci. Čte **bool**. Výchozí hodnota: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Poznámky


Hodnota true vlastnosti určuje návrat k nadřazenému chování navigace v prezentaci. 

Příklad: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Viz také

* Třída [ZoomObject](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)