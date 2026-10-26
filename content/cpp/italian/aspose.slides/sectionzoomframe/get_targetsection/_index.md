---
title: get_TargetSection()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene l'oggetto sezione a cui l'oggetto Section Zoom collega. Leggi ISection.
type: docs
weight: 1
url: /it/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() metodo

Ottiene l'oggetto sezione a cui il [Section](../../section/) Zoom collega. Leggi [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Osservazioni

Il prossimo esempio mostra come modificare la sezione di destinazione e crea una nuova immagine per l'oggetto di zoom della sezione:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISection](../../isection/)
* Classe [SectionZoomFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)