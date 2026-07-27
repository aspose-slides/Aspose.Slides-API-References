---
title: RemoveUnusedLayoutSlides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Realiza la compresión del Presentation eliminando diapositivas de diseño no utilizadas.
type: docs
weight: 14
url: /es/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) método

Realiza la compresión del [Presentation](../../../aspose.slides/presentation/) eliminando diapositivas de diseño no utilizadas.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La instancia de la presentación |
## Comentarios

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [Presentation](../../../aspose.slides/presentation/)
* Clase [Compress](../)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)