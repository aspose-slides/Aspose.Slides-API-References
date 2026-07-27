---
title: FindShape()
second_title: Referência da API Aspose.Slides para C++
description: Encontre a forma por texto alternativo em uma apresentação PPTX.
type: docs
weight: 1
url: /pt/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) method

Encontre a forma por texto alternativo em uma apresentação PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Apresentação escaneada. |
| altText | [System::String](../../../system/string/) | Texto alternativo de uma forma. |

### Valor de Retorno

[Shape](../../../aspose.slides/shape/) ou null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) method

Encontre a forma por texto alternativo em um slide em uma apresentação PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Slide escaneado. |
| altText | [System::String](../../../system/string/) | Texto alternativo de uma forma. |

### Valor de Retorno

[Shape](../../../aspose.slides/shape/) ou null.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [IPresentation](../../../aspose.slides/ipresentation/)
* Classe [String](../../../system/string/)
* Classe [SlideUtil](../)
* Classe [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Namespace [Aspose::Slides::Util](../../)
* Biblioteca [Aspose.Slides](../../../)