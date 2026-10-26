---
title: set_TargetSection()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'oggetto sezione a cui l'oggetto Section Zoom è collegato. Scrivi ISection.
type: docs
weight: 14
url: /it/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metodo

Imposta l'oggetto sezione a cui l'oggetto Zoom [Section](../../section/) è collegato. Scrivi [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Osservazioni

Il prossimo esempio dimostra come modificare la sezione di destinazione e crea una nuova immagine per l'oggetto zoom della sezione:
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
* Library [Aspose.Slides](../../../)