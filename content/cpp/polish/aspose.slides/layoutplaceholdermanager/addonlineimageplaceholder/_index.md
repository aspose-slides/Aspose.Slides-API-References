---
title: AddOnlineImagePlaceholder()
second_title: Referencja API Aspose.Slides dla C++
description: Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać obraz online.
type: docs
weight: 118
url: /pl/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) metoda

Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać obraz online.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu zastępczego. |
| y | **float** | Współrzędna Y nowego kształtu zastępczego. |
| width | **float** | Szerokość nowego kształtu zastępczego. |
| height | **float** | Wysokość nowego kształtu zastępczego. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z zastępstwem obrazu online.

## Uwagi

Poniższy przykład pokazuje, jak dodać kształt zastępczy obrazu online do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [LayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)