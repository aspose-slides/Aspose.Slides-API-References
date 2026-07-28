---
title: get_GridSpacing()
second_title: Aspose.Slides dla C++ odniesienie API
description: Zwraca odstęp siatki, który powinien być używany dla siatki podstawowej dokumentu prezentacji, w punktach. Odczyt float.
type: docs
weight: 92
url: /pl/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() metoda

Zwraca odstęp siatki, który powinien być używany dla siatki podstawowej dokumentu prezentacji, w punktach. Odczyt **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Uwagi

Wartość odstępu siatki musi być liczbą dodatnią. Typowy zakres wartości wynosi od 1 mm (2.8349607 punktów) do 2 cali (144 punktów).

Poniższy kod przykładowy pokazuje, jak zmienić odstęp siatki w prezentacji PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [ViewProperties](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)