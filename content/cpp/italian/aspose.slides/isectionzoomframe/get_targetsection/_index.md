---
title: get_TargetSection()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'oggetto sezione a cui l'oggetto Section Zoom è collegato. Leggi ISection.
type: docs
weight: 1
url: /it/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() method


Restituisce l'oggetto sezione a cui l'oggetto Zoom [Section](../../section/) è collegato. Leggi [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Osservazioni


Questo esempio dimostra la modifica della sezione di destinazione e crea una nuova immagine per l'oggetto di zoom della sezione: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISection](../../isection/)
* Classe [ISectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)