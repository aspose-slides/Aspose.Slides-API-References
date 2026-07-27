---
title: FormatText()
second_title: Referência da API Aspose.Slides para C++
description: Esta função é chamada antes da renderização da parte de texto para SVG para permitir que o usuário controle o SVG resultante.
type: docs
weight: 1
url: /pt/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) método


Esta função é chamada antes da renderização da parte de texto para SVG para permitir que o usuário controle o SVG resultante.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Objeto para controlar a geração de tspan SVG. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Porção de origem. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Quadro de texto da porção de origem. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISvgTSpan](../../isvgtspan/)
* Classe [IPortion](../../../aspose.slides/iportion/)
* Classe [ITextFrame](../../../aspose.slides/itextframe/)
* Classe [ISvgShapeAndTextFormattingController](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)