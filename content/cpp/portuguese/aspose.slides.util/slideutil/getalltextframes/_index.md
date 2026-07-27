---
title: GetAllTextFrames()
second_title: Referência da API Aspose.Slides para C++
description: Retorna todos os quadros de texto em uma apresentação PPTX.
type: docs
weight: 79
url: /pt/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) method

Retorna todos os quadros de texto em uma apresentação PPTX.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Apresentação analisada. |
| withMasters | **bool** | Determina se os slides mestres devem ser escaneados. |

### Valor de Retorno

Matriz de objetos [TextFrame](../../../aspose.slides/textframe/).

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../../aspose.slides/itextframe/)
* Classe [IPresentation](../../../aspose.slides/ipresentation/)
* Classe [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)