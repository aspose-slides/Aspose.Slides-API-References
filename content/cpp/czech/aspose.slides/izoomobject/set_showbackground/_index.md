---
title: set_ShowBackground()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Nastavuje hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Zapište bool. Výchozí hodnota: true"
type: docs
weight: 66
url: /cs/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) metoda


Nastavuje hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Write **bool**. Výchozí hodnota: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## Poznámky


Příklad ukazuje odebrání pozadí obrazu objektu Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Viz také

* Třída [IZoomObject](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)