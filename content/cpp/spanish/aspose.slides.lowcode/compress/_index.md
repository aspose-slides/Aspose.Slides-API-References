---
title: Compress
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un grupo de métodos destinados a comprimir Presentation.
type: docs
weight: 14
url: /es/aspose.slides.lowcode/compress/
---
## Compress clase

Representa un grupo de métodos destinados a comprimir [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Realiza la compresión del [Presentation](../../aspose.slides/presentation/) eliminando caracteres no utilizados de fuentes incrustadas. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Realiza la compresión del [Presentation](../../aspose.slides/presentation/) eliminando diapositivas de diseño no utilizadas. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Realiza la compresión del [Presentation](../../aspose.slides/presentation/) eliminando diapositivas maestras no utilizadas. |
## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Espacio de nombres [Aspose::Slides::LowCode](../)
* Biblioteca [Aspose.Slides](../../)