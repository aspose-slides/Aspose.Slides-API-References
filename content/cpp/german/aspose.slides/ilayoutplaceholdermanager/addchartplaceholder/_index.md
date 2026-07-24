---
title: AddChartPlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein Diagramm zu halten.
type: docs
weight: 66
url: /de/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) Methode


Fügt der Layout-Folien ein neues Platzhalter-Shape hinzu, um ein Chart zu halten.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des neuen Platzhalter-Shape. |
| y | **float** | Die Y-Koordinate des neuen Platzhalter-Shape. |
| width | **float** | Die Breite des neuen Platzhalter-Shape. |
| height | **float** | Die Höhe des neuen Platzhalter-Shape. |

### Rückgabewert

Created [IAutoShape](../../iautoshape/) with a Chart placeholder.
## Anmerkungen



Das folgende Beispiel zeigt, wie das Chart Platzhalter-Shape zur Layout-Folien hinzugefügt wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)