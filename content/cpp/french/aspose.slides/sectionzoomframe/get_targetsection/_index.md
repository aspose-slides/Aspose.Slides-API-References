---
title: get_TargetSection()
second_title: Référence de l'API Aspose.Slides for C++
description: Obtient l'objet de section auquel l'objet Section Zoom est lié. Consultez ISection.
type: docs
weight: 1
url: /fr/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() méthode

Obtient l'objet de section auquel l'objet Zoom [Section](../../section/) se lie. Consultez [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Remarques

L'exemple suivant montre comment changer la section cible et crée une nouvelle image pour l'objet de zoom de section :
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISection](../../isection/)
* Classe [SectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)