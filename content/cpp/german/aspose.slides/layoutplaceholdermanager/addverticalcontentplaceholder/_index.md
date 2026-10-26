---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layout-Folie ein neues Platzhalter-Shape hinzu, um Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung zu halten.
type: docs
weight: 14
url: /de/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) Methode

Fügt der Layout-Folien ein neues Platzhalterform hinzu, um Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung zu halten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate der neuen Platzhalterform. |
| y | **float** | Die Y-Koordinate der neuen Platzhalterform. |
| width | **float** | Die Breite der neuen Platzhalterform. |
| height | **float** | Die Höhe der neuen Platzhalterform. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem Inhalt (Vertikal) Platzhalter.

## Anmerkungen

Das folgende Beispiel zeigt, wie die Content (Vertical) Platzhalterform zur Layout-Folien hinzugefügt wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)