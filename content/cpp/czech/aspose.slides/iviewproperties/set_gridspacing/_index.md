---
title: set_GridSpacing()
second_title: Aspose.Slides pro C++ – reference API
description: Nastavuje rozteč mřížky, která má být použita pro mřížku podkladovou dokumentu prezentace, v bodech. Zapište float.
type: docs
weight: 105
url: /cs/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) metoda


Nastavuje rozteč mřížky, která by měla být použita pro mřížku podkladovou prezentace, v bodech. Zapište **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Poznámky


Hodnota rozteče mřížky musí být kladné číslo. Typický rozsah hodnot je od 1 mm (2.8349607 bodů) do 2 palců (144 bodů). 

Následující ukázkový kód ukazuje, jak změnit rozteč mřížky v prezentaci PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [IViewProperties](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)