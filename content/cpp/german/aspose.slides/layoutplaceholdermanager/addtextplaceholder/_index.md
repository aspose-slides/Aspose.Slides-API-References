---
title: AddTextPlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layout-Folie eine neue Platzhalterform hinzu, um Textinhalt zu halten.
type: docs
weight: 27
url: /de/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) Methode

Fügt der Layout-Folienfolie eine neue Platzhalterform hinzu, um Textinhalt zu halten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate der neuen Platzhalterform. |
| y | **float** | Die Y-Koordinate der neuen Platzhalterform. |
| width | **float** | Die width der neuen Platzhalterform. |
| height | **float** | Die height der neuen Platzhalterform. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem Text-Platzhalter.

## Bemerkungen

Das folgende Beispiel zeigt, wie die Text-Platzhalterform zur Layout-Folienfolie hinzugefügt wird.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)