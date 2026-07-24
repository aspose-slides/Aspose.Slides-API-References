---
title: AddPicturePlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layoutfolie eine neue Platzhalterform hinzu, um ein Bild zu halten.
type: docs
weight: 53
url: /de/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) method

Fügt der Layoutfolie eine neue Platzhalterform hinzu, um ein Bild zu halten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate der neuen Platzhalterform. |
| y | **float** | Die Y-Koordinate der neuen Platzhalterform. |
| width | **float** | Die Breite der neuen Platzhalterform. |
| height | **float** | Die Höhe der neuen Platzhalterform. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem [Picture](../../picture/) Platzhalter.

## Bemerkungen

Das folgende Beispiel zeigt, wie die [Picture](../../picture/) Platzhalterform zur Layoutfolie hinzugefügt wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)