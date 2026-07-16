---
title: set_TargetSection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'objet de section auquel l'objet Section Zoom est lié. Écrit ISection.
type: docs
weight: 14
url: /fr/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) méthode

Définit l'objet de section auquel l'objet Zoom [Section](../../section/) est lié. Écrit [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Remarques

Cet exemple montre la modification de la section cible et crée une nouvelle image pour l'objet de zoom de section :
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISection](../../isection/)
* Classe [ISectionZoomFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)