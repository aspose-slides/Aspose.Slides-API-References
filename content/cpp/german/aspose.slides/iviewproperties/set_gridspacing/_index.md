---
title: set_GridSpacing()
second_title: Aspose.Slides für C++ API Referenz
description: Legt den Rasterabstand fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Schreiben Sie float.
type: docs
weight: 105
url: /de/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) Methode


Legt den Rasterabstand fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Schreiben Sie **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Hinweise


Der Rasterabstand muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2.8349607 Punkte) und 2 Zoll (144 Punkte). 

Der folgende Beispielcode zeigt, wie der Rasterabstand in einer PowerPoint-Präsentation geändert werden kann. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [IViewProperties](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)