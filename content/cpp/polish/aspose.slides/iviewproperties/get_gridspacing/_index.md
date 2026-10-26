---
title: get_GridSpacing()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. Odczyt float.
type: docs
weight: 92
url: /pl/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() metoda


Zwraca odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. Odczyt **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Uwagi


Wartość odstępu siatki musi być liczbą dodatnią. Typowy zakres wartości wynosi od 1 mm (2.8349607 punktów) do 2 cali (144 punktów). 

Poniższy przykładowy kod pokazuje, jak zmienić odstęp siatki w prezentacji PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [IViewProperties](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)