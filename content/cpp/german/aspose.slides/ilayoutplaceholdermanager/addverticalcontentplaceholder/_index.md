---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layout-Folie einen neuen Platzhalter hinzu, um Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung zu halten.
type: docs
weight: 14
url: /de/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) Methode

Fügt der Layout-Folie eine neue Platzhalter-Form hinzu, um Inhalte wie ein Bild, eine Tabelle, Medien oder Text in vertikaler Richtung zu halten.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate der neuen Platzhalter-Form. |
| y | **float** | Die Y-Koordinate der neuen Platzhalter-Form. |
| width | **float** | Die Breite der neuen Platzhalter-Form. |
| height | **float** | Die Höhe der neuen Platzhalter-Form. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem Inhalt (Vertikal) Platzhalter.

## Bemerkungen

Das folgende Beispiel zeigt, wie die Inhalt (Vertikal) Platzhalter-Form zur Layout-Folie hinzugefügt wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ILayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)