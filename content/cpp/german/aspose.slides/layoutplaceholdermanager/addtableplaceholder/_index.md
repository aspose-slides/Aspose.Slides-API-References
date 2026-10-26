---
title: AddTablePlaceholder()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Layout-Folie eine neue Platzhalterform hinzu, um eine Tabelle zu enthalten.
type: docs
weight: 79
url: /de/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) Methode


Fügt der Layout-Folie eine neue Platzhalterform hinzu, um eine Tabelle zu enthalten.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate der neuen Platzhalterform. |
| y | **float** | Die Y-Koordinate der neuen Platzhalterform. |
| width | **float** | Die Breite der neuen Platzhalterform. |
| height | **float** | Die Höhe der neuen Platzhalterform. |

### Rückgabewert

Erstellt [IAutoShape](../../iautoshape/) mit einem [Table](../../table/) Platzhalter.
## Bemerkungen



Das folgende Beispiel zeigt, wie man die [Table](../../table/) Platzhalterform zur Layout-Folie hinzufügt. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [LayoutPlaceholderManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)