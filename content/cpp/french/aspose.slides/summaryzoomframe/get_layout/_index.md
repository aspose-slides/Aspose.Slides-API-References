---
title: get_Layout()
second_title: Référence API Aspose.Slides pour C++
description: Obtient la disposition des Summary Zoom Sections dans le cadre. La valeur par défaut est GridLayout.
type: docs
weight: 1
url: /fr/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() méthode


Obtient la disposition des Summary Zoom Sections dans le cadre. La valeur par défaut est GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
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

* Énum [ZoomLayout](../../zoomlayout/)
* Classe [SummaryZoomFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)