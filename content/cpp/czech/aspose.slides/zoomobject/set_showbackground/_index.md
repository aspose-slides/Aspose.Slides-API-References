---
title: set_ShowBackground()
second_title: Aspose.Slides pro C++ API Reference
description: "Nastavuje hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Zapisujte bool. Výchozí hodnota: true"
type: docs
weight: 66
url: /cs/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) metoda

Nastavuje hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Zapisujte **bool**. Výchozí hodnota: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
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

* Třída [ZoomObject](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)