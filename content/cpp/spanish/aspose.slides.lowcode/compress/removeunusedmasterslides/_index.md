---
title: RemoveUnusedMasterSlides()
second_title: Referencia de API de Aspose.Slides para C++
description: Realiza la compresión de la Presentation eliminando diapositivas maestras no utilizadas.
type: docs
weight: 1
url: /es/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) método

Realiza la compresión del [Presentation](../../../aspose.slides/presentation/) eliminando las diapositivas maestras no utilizadas.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La instancia de la presentación |
## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Presentation](../../../aspose.slides/presentation/)
* Clase [Compress](../)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)