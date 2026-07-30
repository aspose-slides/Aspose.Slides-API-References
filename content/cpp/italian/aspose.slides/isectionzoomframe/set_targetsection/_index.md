---
title: set_TargetSection()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'oggetto sezione a cui è collegato l'oggetto Section Zoom. Scrivi ISection.
type: docs
weight: 14
url: /it/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metodo

Imposta l'oggetto sezione a cui è collegato l'oggetto [Section](../../section/) Zoom. Scrivi [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Note

Questo esempio dimostra come modificare la sezione di destinazione e crea una nuova immagine per l'oggetto zoom della sezione:
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
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)