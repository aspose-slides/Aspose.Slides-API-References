---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layoutfolie eine neue Platzhalterform hinzu, um Textinhalt in vertikaler Richtung zu halten.
type: docs
weight: 40
url: /de/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) Methode


Fügt der Layoutfolie eine neue Platzhalterform hinzu, um Textinhalt in vertikaler Richtung zu halten.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate der neuen Platzhalterform. |
| y | **float** | Die Y-Koordinate der neuen Platzhalterform. |
| width | **float** | Die Breite der neuen Platzhalterform. |
| height | **float** | Die Höhe der neuen Platzhalterform. |

### Rückgabewert

Erstellte [IAutoShape](../../iautoshape/) mit einem Text (Vertical) Platzhalter.
## Hinweise



Das folgende Beispiel zeigt, wie man die Text (Vertical) Platzhalterform zur Layoutfolie hinzufügt.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ILayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)