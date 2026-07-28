---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides dla C++ – referencja API
description: Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać zawartość tekstową w pionowym kierunku.
type: docs
weight: 40
url: /pl/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) metoda


Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać zawartość tekstową w pionowym kierunku.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu zastępczego. |
| y | **float** | Współrzędna Y nowego kształtu zastępczego. |
| width | **float** | Szerokość nowego kształtu zastępczego. |
| height | **float** | Wysokość nowego kształtu zastępczego. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z tekstowym (pionowym) miejscem zastępczym.

## Uwagi



Poniższy przykład pokazuje, jak dodać kształt tekstowego (pionowego) miejsca zastępczego do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [LayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)