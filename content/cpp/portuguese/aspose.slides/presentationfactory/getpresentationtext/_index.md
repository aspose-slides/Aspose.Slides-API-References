---
title: GetPresentationText()
second_title: Referência da API Aspose.Slides para C++
description: Recupera o texto bruto dos slides
type: docs
weight: 53
url: /pt/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) método

Recupera o texto bruto dos slides

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Arquivo de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modo de extração |

### Valor de Retorno

A instância de [PresentationText](../../presentationtext/) contendo o array SlideText que representa o texto bruto dos slides

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) método

Recupera o texto bruto dos slides

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modo de extração |

### Valor de Retorno

A instância de [PresentationText](../../presentationtext/) contendo o array SlideText que representa o texto bruto dos slides

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) método

Recupera o texto bruto dos slides

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Modo de extração |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opções de carregamento |

### Valor de Retorno

A instância de [PresentationText](../../presentationtext/) contendo o array SlideText que representa o texto bruto dos slides

## Veja Também

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationText](../../ipresentationtext/)
* Classe [String](../../../system/string/)
* Classe [PresentationFactory](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)