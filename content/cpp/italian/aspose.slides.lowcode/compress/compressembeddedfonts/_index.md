---
title: CompressEmbeddedFonts()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue la compressione della Presentation rimuovendo i caratteri inutilizzati dai font incorporati.
type: docs
weight: 27
url: /it/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) metodo

Esegue la compressione del [Presentation](../../../aspose.slides/presentation/) rimuovendo i caratteri inutilizzati dai font incorporati.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | L'istanza della presentazione |
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [Compress](../)
* Spazio dei nomi [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)