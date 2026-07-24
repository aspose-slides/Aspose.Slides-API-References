---
title: AddPicturePlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, um ein Bild zu halten.
type: docs
weight: 53
url: /de/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) Methode

Fügt der Layoutfolie ein neues Platzhalter-Shape hinzu, um ein Bild zu halten.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | **float** | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | **float** | Die Breite des neuen Platzhalter-Shapes. |
| height | **float** | Die Höhe des neuen Platzhalter-Shapes. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem [Picture](../../picture/) Platzhalter.

## Hinweise



Das folgende Beispiel zeigt, wie man das [Picture](../../picture/) Platzhalter-Shape zur Layoutfolie hinzufügt. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ILayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)