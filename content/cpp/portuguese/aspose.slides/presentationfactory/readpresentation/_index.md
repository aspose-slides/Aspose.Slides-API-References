---
title: ReadPresentation()
second_title: Referência da API Aspose.Slides para C++
description: Lê uma apresentação existente a partir de um array
type: docs
weight: 40
url: /pt/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) método


Lê uma apresentação existente a partir de um array

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array a ser lido |

### Valor de Retorno

Apresentação lida

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) método


Lê uma apresentação existente a partir de um array com opções de carregamento adicionais

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array a ser lido |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opções de carregamento |

### Valor de Retorno

Apresentação lida

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) método


Lê uma apresentação existente a partir de um stream

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de entrada a ser lido |

### Valor de Retorno

Apresentação lida

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) método


Lê uma apresentação existente a partir de um stream com opções de carregamento adicionais

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de entrada a ser lido |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opções de carregamento |

### Valor de Retorno

Apresentação lida

## PresentationFactory::ReadPresentation(System::String) método


Lê uma apresentação existente a partir de um arquivo

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nome do arquivo |

### Valor de Retorno

Apresentação lida

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) método


Lê uma apresentação existente a partir de um arquivo com opções de carregamento adicionais

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nome do arquivo |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opções de carregamento |

### Valor de Retorno

Apresentação lida

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* classe [IPresentation](../../ipresentation/)
* classe [PresentationFactory](../)
* classe [ILoadOptions](../../iloadoptions/)
* classe [Stream](../../../system.io/stream/)
* classe [String](../../../system/string/)
* namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)