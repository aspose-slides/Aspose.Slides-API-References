---
title: AddSmartArtPlaceholder()
second_title: Odwołanie API Aspose.Slides dla C++
description: Dodaje nowy kształt zastępczy do slajdu układu, aby pomieścić diagram SmartArt.
type: docs
weight: 92
url: /pl/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) metoda

Dodaje nowy kształt zastępczy do slajdu układu, aby pomieścić diagram [SmartArt](../../../aspose.slides.smartart/).

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu zastępczego. |
| y | **float** | Współrzędna Y nowego kształtu zastępczego. |
| width | **float** | Szerokość nowego kształtu zastępczego. |
| height | **float** | Wysokość nowego kształtu zastępczego. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z [SmartArt](../../../aspose.slides.smartart/) zastępczym.

## Uwagi

Poniższy przykład pokazuje, jak dodać kształt zastępczy [SmartArt](../../../aspose.slides.smartart/) do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [LayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)