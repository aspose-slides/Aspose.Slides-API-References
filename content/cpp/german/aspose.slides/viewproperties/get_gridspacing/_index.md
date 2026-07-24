---
title: get_GridSpacing()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Rasterabstand zurück, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Lies float.
type: docs
weight: 92
url: /de/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() Methode

Gibt den Rasterabstand zurück, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Lesen **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Hinweise

Der Rasterabstand muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2.8349607 Punkte) und 2 Zoll (144 Punkte).

Der folgende Beispielcode zeigt, wie der Rasterabstand in einer PowerPoint-Präsentation geändert wird.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [ViewProperties](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)