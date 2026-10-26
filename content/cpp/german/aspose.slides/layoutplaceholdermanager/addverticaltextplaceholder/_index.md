---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Textinhalt in vertikaler Richtung zu halten.
type: docs
weight: 40
url: /de/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) Methode

Fügt der Layout-Folien ein neues Platzhalter-Shape hinzu, um Textinhalt in vertikaler Richtung zu halten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | **float** | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | **float** | Die Breite des neuen Platzhalter-Shapes. |
| height | **float** | Die Höhe des neuen Platzhalter-Shapes. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem Text (Vertikal) Platzhalter.

## Anmerkungen

Das folgende Beispiel zeigt, wie das Text (Vertikal) Platzhalter-Shape zur Layout-Folien hinzugefügt wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)