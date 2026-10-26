---
title: AddChartPlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layoutfolie einen neuen Platzhalter-Shape hinzu, um ein Diagramm zu halten.
type: docs
weight: 66
url: /de/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) Methode

Fügt der Layoutfolie einen neuen Platzhalter-Shape hinzu, um ein Chart zu halten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des neuen Platzhalter-Shape. |
| y | **float** | Die Y-Koordinate des neuen Platzhalter-Shape. |
| width | **float** | Die Breite des neuen Platzhalter-Shape. |
| height | **float** | Die Höhe des neuen Platzhalter-Shape. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem Chart-Platzhalter.

## Hinweise

Das folgende Beispiel zeigt, wie man das Chart-Platzhalter-Shape zur Layoutfolie hinzufügt.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)