---
title: AddChartPlaceholder()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový tvar zástupce do snímku rozložení, který bude obsahovat graf.
type: docs
weight: 66
url: /cs/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) metoda


Přidá nový tvar zástupce do snímku rozložení pro umístění grafu.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Souřadnice X nového tvaru zástupce. |
| y | **float** | Souřadnice Y nového tvaru zástupce. |
| width | **float** | Šířka nového tvaru zástupce. |
| height | **float** | Výška nového tvaru zástupce. |

### Návratová hodnota

Vytvořen [IAutoShape](../../iautoshape/) s Chart placeholder.

## Poznámky



Následující příklad ukazuje, jak přidat tvar Chart placeholder do rozložení snímku. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)