---
title: AddMediaPlaceholder()
second_title: Aspose.Slides dla interfejsu API C++
description: Dodaje nowy kształt placeholdera do slajdu układu, aby przechowywać obiekt multimedialny.
type: docs
weight: 105
url: /pl/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) metoda


Dodaje nowy kształt placeholdera do slajdu układu, aby przechowywać obiekt multimedialny.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu placeholdera. |
| y | **float** | Współrzędna Y nowego kształtu placeholdera. |
| width | **float** | Szerokość nowego kształtu placeholdera. |
| height | **float** | Wysokość nowego kształtu placeholdera. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z placeholderem Media.
## Uwagi



Poniższy przykład pokazuje, jak dodać kształt placeholdera Media do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [LayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)