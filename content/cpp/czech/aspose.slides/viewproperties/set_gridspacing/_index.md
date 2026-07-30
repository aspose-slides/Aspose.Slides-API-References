---
title: set_GridSpacing()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje rozestup mřížky, který by měl být použit pro mřížku podkladu prezentačního dokumentu, v bodech. Zapište float.
type: docs
weight: 105
url: /cs/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) method


Nastavuje rozestup mřížky, který by měl být použit pro mřížku podkladu prezentačního dokumentu, v bodech. Zapište **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
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

* Třída [ViewProperties](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)