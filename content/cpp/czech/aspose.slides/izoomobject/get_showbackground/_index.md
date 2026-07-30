---
title: get_ShowBackground()
second_title: Aspose.Slides pro C++ API Reference
description: "Získá hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Čte bool. Výchozí hodnota: true"
type: docs
weight: 53
url: /cs/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() metoda

Získá hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Čte **bool**. Výchozí hodnota: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Poznámky

Příklad ukazuje odstranění pozadí obrázku objektu Zoom:
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