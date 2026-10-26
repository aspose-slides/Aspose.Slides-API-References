---
title: set_GridSpacing()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. Zapisz float.
type: docs
weight: 105
url: /pl/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) metoda


Ustawia odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. Zapisz **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
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

* Klasa [ViewProperties](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)