---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um ein SmartArt-Diagramm zu halten.
type: docs
weight: 92
url: /de/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) Methode

Fügt der Layout-Folien ein neues Platzhalter-Shape hinzu, um ein [SmartArt](../../../aspose.slides.smartart/)-Diagramm zu halten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | **float** | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | **float** | Die Breite des neuen Platzhalter-Shapes. |
| height | **float** | Die Höhe des neuen Platzhalter-Shapes. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem [SmartArt](../../../aspose.slides.smartart/)-Platzhalter.

## Hinweis

Das folgende Beispiel zeigt, wie das [SmartArt](../../../aspose.slides.smartart/)-Platzhalter-Shape zur Layout-Folien hinzugefügt wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)