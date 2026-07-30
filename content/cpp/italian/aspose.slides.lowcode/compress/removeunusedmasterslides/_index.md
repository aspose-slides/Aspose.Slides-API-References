---
title: RemoveUnusedMasterSlides()
second_title: Riferimento API Aspose.Slides per C++
description: Esegue la compressione della Presentation rimuovendo le diapositive master inutilizzate.
type: docs
weight: 1
url: /it/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) metodo


Esegue la compressione di [Presentation](../../../aspose.slides/presentation/) rimuovendo le diapositive master inutilizzate.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | L'istanza della presentazione |
## Osservazioni




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [Compress](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)