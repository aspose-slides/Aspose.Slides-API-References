---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layoutfolie eine neue Platzhalterform hinzu, um ein Online-Bild zu halten.
type: docs
weight: 118
url: /de/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) Methode

Fügt der Layoutfolie eine neue Platzhalterform hinzu, um ein Online Image zu halten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate der neuen Platzhalterform. |
| y | **float** | Die Y-Koordinate der neuen Platzhalterform. |
| width | **float** | Die Breite der neuen Platzhalterform. |
| height | **float** | Die Höhe der neuen Platzhalterform. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem Online Image-Platzhalter.

## Bemerkungen

Das folgende Beispiel zeigt, wie man die Online Image-Platzhalterform zur Layoutfolie hinzufügt. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)