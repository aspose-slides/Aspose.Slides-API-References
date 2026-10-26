---
title: WriteShapeEnd()
second_title: Aspose.Slides para Referência da API C++
description: Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será concluída, o fragmento HTML adicionado será inserido e uma nova imagem será iniciada sobre a anterior.
type: docs
weight: 79
url: /pt/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) method

Chamado antes da renderização da forma. Chamado uma vez para cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será finalizada, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
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
* Classe [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)