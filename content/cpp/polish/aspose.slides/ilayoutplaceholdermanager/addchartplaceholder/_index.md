---
title: AddChartPlaceholder()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dodaje nowy kształt zastępczy do slajdu układu, aby pomieścić wykres.
type: docs
weight: 66
url: /pl/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) metoda

Dodaje nowy kształt zastępczy do slajdu układu, aby pomieścić wykres.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu zastępczego. |
| y | **float** | Współrzędna Y nowego kształtu zastępczego. |
| width | **float** | Szerokość nowego kształtu zastępczego. |
| height | **float** | Wysokość nowego kształtu zastępczego. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z zastępcą wykresu.

## Uwagi

Poniższy przykład pokazuje, jak dodać kształt zastępczy wykresu do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [ILayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)