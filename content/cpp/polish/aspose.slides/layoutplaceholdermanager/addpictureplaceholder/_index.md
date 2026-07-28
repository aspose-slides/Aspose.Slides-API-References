---
title: AddPicturePlaceholder()
second_title: Odwołanie API Aspose.Slides dla C++
description: Dodaje nowy kształt zastępczy do slajdu układu, aby pomieścić obraz.
type: docs
weight: 53
url: /pl/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) metoda


Dodaje nowy kształt zastępczy do slajdu układu, aby pomieścić obraz.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu zastępczego. |
| y | **float** | Współrzędna Y nowego kształtu zastępczego. |
| width | **float** | Szerokość nowego kształtu zastępczego. |
| height | **float** | Wysokość nowego kształtu zastępczego. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z [Picture](../../picture/) zastępczem.
## Uwagi



Poniższy przykład pokazuje, jak dodać kształt zastępczy [Picture](../../picture/) do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [LayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)