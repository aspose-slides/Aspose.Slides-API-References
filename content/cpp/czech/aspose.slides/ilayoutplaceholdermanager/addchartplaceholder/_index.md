---
title: AddChartPlaceholder()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá nový placeholder tvar do rozložení snímku, aby obsahoval graf.
type: docs
weight: 66
url: /cs/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) method

Přidá nový placeholder tvar do rozložení snímku, aby obsahoval graf.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Souřadnice X nového placeholder tvaru. |
| y | **float** | Souřadnice Y nového placeholder tvaru. |
| width | **float** | Šířka nového placeholder tvaru. |
| height | **float** | Výška nového placeholder tvaru. |

### Návratová hodnota

Vytvořeno [IAutoShape](../../iautoshape/) s placeholderem Chart.

## Poznámky

Následující příklad ukazuje, jak přidat placeholder tvar Chart do rozložení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)