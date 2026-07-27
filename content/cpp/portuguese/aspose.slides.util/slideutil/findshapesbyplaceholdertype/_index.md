---
title: FindShapesByPlaceholderType()
second_title: Aspose.Slides para C++ Referência da API
description: Procura todas as formas no slide especificado que correspondem ao tipo de placeholder fornecido.
type: docs
weight: 14
url: /pt/aspose.slides.util/slideutil/findshapesbyplaceholdertype/
---
## SlideUtil::FindShapesByPlaceholderType(System::SharedPtr\<IBaseSlide\>, PlaceholderType) método


Procura todas as formas no slide especificado que correspondem ao tipo de placeholder fornecido.

```cpp
static System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::Util::SlideUtil::FindShapesByPlaceholderType(System::SharedPtr<IBaseSlide> slide, PlaceholderType placeholderType)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | O slide onde procurar as formas. |
| placeholderType | [PlaceholderType](../../../aspose.slides/placeholdertype/) | O tipo de placeholder usado para filtrar as formas. |

### Return Value

Uma matriz de objetos [IShape](../../../aspose.slides/ishape/) que correspondem ao tipo de placeholder especificado.

## See Also

* Enum [PlaceholderType](../../../aspose.slides/placeholdertype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Classe [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Biblioteca [Aspose.Slides](../../../)