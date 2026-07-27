---
title: CompressEmbeddedFonts()
second_title: Referencia de API de Aspose.Slides para C++
description: Realiza la compresión de la Presentation eliminando los caracteres no utilizados de las fuentes incrustadas.
type: docs
weight: 27
url: /es/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) método


Realiza la compresión del [Presentation](../../../aspose.slides/presentation/) eliminando los caracteres no utilizados de las fuentes incrustadas.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La instancia de presentación |
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [Presentation](../../../aspose.slides/presentation/)
* Clase [Compress](../)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)