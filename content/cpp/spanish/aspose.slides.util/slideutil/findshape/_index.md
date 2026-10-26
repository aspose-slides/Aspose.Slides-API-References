---
title: FindShape()
second_title: Referencia de la API de Aspose.Slides para C++
description: Buscar forma por texto alternativo en una presentación PPTX.
type: docs
weight: 1
url: /es/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) método


Buscar forma por texto alternativo en una presentación PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Presentación escaneada. |
| altText | [System::String](../../../system/string/) | Texto alternativo de una forma. |

### Valor devuelto

[Shape](../../../aspose.slides/shape/) o null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) método


Buscar forma por texto alternativo en una diapositiva de una presentación PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Diapositiva escaneada. |
| altText | [System::String](../../../system/string/) | Texto alternativo de una forma. |

### Valor devuelto

[Shape](../../../aspose.slides/shape/) o null.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShape](../../../aspose.slides/ishape/)
* Clase [IPresentation](../../../aspose.slides/ipresentation/)
* Clase [String](../../../system/string/)
* Clase [SlideUtil](../)
* Clase [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Espacio de nombres [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)