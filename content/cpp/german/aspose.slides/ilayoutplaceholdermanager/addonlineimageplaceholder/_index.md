---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layout-Folie einen neuen Platzhalter-Shape hinzu, um ein Online-Image zu halten.
type: docs
weight: 118
url: /de/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) Methode

Fügt der Layout-Folien-Form einen neuen Platzhalter-Shape hinzu, um ein Online-Image zu halten.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des neuen Platzhalter-Shapes. |
| y | **float** | Die Y-Koordinate des neuen Platzhalter-Shapes. |
| width | **float** | Die Breite des neuen Platzhalter-Shapes. |
| height | **float** | Die Höhe des neuen Platzhalter-Shapes. |

### Rückgabewert

Erstellte [IAutoShape](../../iautoshape/) mit einem Online Image-Platzhalter.

## Bemerkungen

Das folgende Beispiel zeigt, wie man das Online Image-Platzhalter-Shape zur Layout-Folie hinzufügt. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)