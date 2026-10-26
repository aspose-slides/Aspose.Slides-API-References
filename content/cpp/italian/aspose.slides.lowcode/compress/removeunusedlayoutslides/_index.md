---
title: RemoveUnusedLayoutSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue la compressione della Presentation rimuovendo le diapositive di layout non utilizzate.
type: docs
weight: 14
url: /it/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) metodo

Esegue la compressione del [Presentation](../../../aspose.slides/presentation/) rimuovendo le diapositive di layout non utilizzate.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | L'istanza della presentazione |

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [Compress](../)
* Spazio dei nomi [Aspose::Slides::LowCode](../../)
* Libreria [Aspose.Slides](../../../)