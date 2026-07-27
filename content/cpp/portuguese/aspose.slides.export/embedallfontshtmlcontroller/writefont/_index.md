---
title: WriteFont()
second_title: Referência da API Aspose.Slides para C++
description: Escreve dados como base64 no próprio documento HTML
type: docs
weight: 105
url: /pt/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) método

Escreve dados como base64 no próprio documento HTML

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | gerador HTML |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Fonte a ser serializada |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Fonte substituída (se a substituição de fonte ocorreu), null caso contrário |
| fontStyle | [System::String](../../../system/string/) | Estilo da fonte |
| fontWeight | [System::String](../../../system/string/) | Peso da fonte |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dados da fonte |

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IFontData](../../../aspose.slides/ifontdata/)
* Classe [String](../../../system/string/)
* Classe [EmbedAllFontsHtmlController](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)