---
title: AddTextPlaceholder()
second_title: Aspose.Slides dla C++ Referencja API
description: Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać zawartość tekstową.
type: docs
weight: 27
url: /pl/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) metoda

Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać zawartość tekstową.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu placeholder. |
| y | **float** | Współrzędna Y nowego kształtu placeholder. |
| width | **float** | Szerokość nowego kształtu placeholder. |
| height | **float** | Wysokość nowego kształtu placeholder. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z placeholderem Text.

## Uwagi



Poniższy przykład pokazuje, jak dodać kształt placeholder Text do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [ILayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)