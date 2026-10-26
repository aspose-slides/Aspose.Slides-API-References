---
title: GetPresentationText()
second_title: Referência da API Aspose.Slides para C++
description: Recupera o texto bruto dos slides
type: docs
weight: 40
url: /pt/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method

Recupera o texto bruto dos slides

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | arquivo de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | modo de extração |

### Valor de retorno

A instância de [PresentationText](../../presentationtext/) contendo o array SlideText que representa o texto bruto dos slides

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method

Recupera o texto bruto dos slides

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | fluxo de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | modo de extração |

### Valor de retorno

A instância de [PresentationText](../../presentationtext/) contendo o array SlideText que representa o texto bruto dos slides

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method

Recupera o texto bruto dos slides

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | fluxo de entrada |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | modo de extração |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | opções de carregamento |

### Valor de retorno

A instância de [PresentationText](../../presentationtext/) contendo o array SlideText que representa o texto bruto dos slides

## Veja Também

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationText](../../ipresentationtext/)
* Classe [String](../../../system/string/)
* Classe [IPresentationFactory](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [ILoadOptions](../../iloadoptions/)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)