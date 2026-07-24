---
title: set_GridSpacing()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt den Rasterabstand fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Write float.
type: docs
weight: 105
url: /de/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) Methode

Legt den Rasterabstand fest, der für das dem Präsentationsdokument zugrunde liegende Raster verwendet werden soll, in Punkten. Schreiben Sie **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Anmerkungen

Der Rasterabstandswert muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2.8349607 Punkte) und 2 Zoll (144 Punkte).

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