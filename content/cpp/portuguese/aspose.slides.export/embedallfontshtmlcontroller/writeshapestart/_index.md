---
title: WriteShapeStart()
second_title: Referência da API Aspose.Slides para C++
description: Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no generator, a geração da imagem do slide atual será concluída, o fragmento html adicionado será inserido e uma nova imagem será iniciada acima da anterior.
type: docs
weight: 66
url: /pt/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) método

Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no generator, a geração da imagem do slide atual será concluída, o fragmento html adicionado será inserido e uma nova imagem será iniciada acima da anterior.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objeto de saída. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) que está prestes a ser renderizada. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)