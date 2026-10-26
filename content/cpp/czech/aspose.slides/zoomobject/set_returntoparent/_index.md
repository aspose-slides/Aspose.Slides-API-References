---
title: set_ReturnToParent()
second_title: Aspose.Slides pro C++ referenci API
description: "Nastavuje chování navigace v prezentaci. Zapište bool. Výchozí hodnota: false"
type: docs
weight: 40
url: /cs/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) metoda

Sets the navigation behavior in slideshow. Write **bool**. Default value: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Poznámky

True hodnota vlastnosti určuje návrat k rodičovskému chování navigace v prezentaci. 

Příklad: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Viz také

* Třída [ZoomObject](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)