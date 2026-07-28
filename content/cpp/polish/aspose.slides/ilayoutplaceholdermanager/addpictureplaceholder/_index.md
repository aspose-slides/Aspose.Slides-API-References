---
title: AddPicturePlaceholder()
second_title: Aspose.Slides for C++ – Referencja API
description: Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać obraz.
type: docs
weight: 53
url: /pl/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) metoda

Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać obraz.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu zastępczego. |
| y | **float** | Współrzędna Y nowego kształtu zastępczego. |
| width | **float** | Szerokość nowego kształtu zastępczego. |
| height | **float** | Wysokość nowego kształtu zastępczego. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z [Picture](../../picture/) zastępcą.

## Uwagi

Poniższy przykład pokazuje, jak dodać kształt [Picture](../../picture/) zastępczy do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [ILayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)