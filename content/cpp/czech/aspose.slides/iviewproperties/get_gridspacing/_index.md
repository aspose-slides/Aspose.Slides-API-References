---
title: get_GridSpacing()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací rozestup mřížky, který by měl být použit pro mřížku podkladovou prezentačního dokumentu, v bodech. Číst float.
type: docs
weight: 92
url: /cs/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() metoda


Vrací rozestup mřížky, který by měl být použit pro mřížku podkladovou prezentačního dokumentu, v bodech. Číst **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Poznámky


Hodnota rozestupu mřížky musí být kladné číslo. Typický rozsah hodnot je od 1 mm (2.8349607 bodů) do 2 palců (144 bodů). 

Následující ukázkový kód ukazuje, jak změnit rozestup mřížky v prezentaci PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [IViewProperties](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)