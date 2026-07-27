---
title: WriteShapeEnd()
second_title: Referência da API Aspose.Slides para C++
description: Chamado antes da renderização da shape. Chamado uma vez para cada shape. Se esta função escrever algo no generator, a geração da imagem do slide atual será concluída, o fragmento HTML adicionado será inserido e uma nova imagem será iniciada sobre a anterior.
type: docs
weight: 66
url: /pt/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) método

Chamado antes da renderização da shape. Chamado uma vez para cada shape. Se esta função escrever algo no generator, a geração da imagem do slide atual será concluída, o fragmento HTML adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objeto de saída. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) que é renderizado por último. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [IHtmlFormattingController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)