---
title: WriteShapeStart()
second_title: Aspose.Slides para C++ Referência da API
description: Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será concluída, o fragmento HTML adicionado será inserido e uma nova imagem será iniciada sobre a anterior.
type: docs
weight: 53
url: /pt/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) método

Chamado antes da renderização da forma. Chamado uma vez por cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será concluída, o fragmento HTML adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objeto de saída. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) que está prestes a ser renderizado. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [IHtmlFormattingController](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)