---
title: get_Layout()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la disposition des sections Summary Zoom dans le cadre. La valeur par défaut est GridLayout.
type: docs
weight: 1
url: /fr/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() méthode

Obtient la disposition des sections de Summary Zoom dans le cadre. La valeur par défaut est GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Remarques

L'exemple montre comment obtenir l'élément Summary Zoom [Section](../../section/) par indice :

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Voir aussi

* Enum [ZoomLayout](../../zoomlayout/)
* Class [ISummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)