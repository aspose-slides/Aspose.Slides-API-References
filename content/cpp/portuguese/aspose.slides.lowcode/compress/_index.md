---
title: Compress
second_title: Referência da API Aspose.Slides para C++
description: Representa um grupo de métodos destinados a compactar Presentation.
type: docs
weight: 14
url: /pt/aspose.slides.lowcode/compress/
---
## Compress classe


Representa um grupo de métodos destinados a compactar [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Faz a compactação do [Presentation](../../aspose.slides/presentation/) removendo caracteres não utilizados de fontes incorporadas. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Faz a compactação do [Presentation](../../aspose.slides/presentation/) removendo slides de layout não utilizados. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Faz a compactação do [Presentation](../../aspose.slides/presentation/) removendo slides mestres não utilizados. |
## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Namespace [Aspose::Slides::LowCode](../)
* Biblioteca [Aspose.Slides](../../)