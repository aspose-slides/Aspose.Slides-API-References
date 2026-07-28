---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides dla C++ – referencja API
description: Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać obraz online.
type: docs
weight: 118
url: /pl/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) metoda

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać obraz online.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | **float** | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | **float** | Szerokość nowego kształtu symbolu zastępczego. |
| height | **float** | Wysokość nowego kształtu symbolu zastępczego. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z symbolem zastępczym obrazu online.

## Uwagi

Poniższy przykład pokazuje, jak dodać kształt symbolu zastępczego obrazu online do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [ILayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)