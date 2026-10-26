---
title: ReadPresentation()
second_title: Referência da API Aspose.Slides para C++
description: Lê uma apresentação existente a partir de um array
type: docs
weight: 27
url: /pt/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) método

Lê uma apresentação existente a partir de um array

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array a ser lido |

### Valor de retorno

Apresentação lida

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) método

Lê uma apresentação existente a partir de um array com opções de carregamento adicionais

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array a ser lido |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opções de carregamento |

### Valor de retorno

Apresentação lida

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) método

Lê uma apresentação existente a partir de um stream

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de entrada a ser lido |

### Valor de retorno

Apresentação lida

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) método

Lê uma apresentação existente a partir de um stream com opções de carregamento adicionais

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de entrada a ser lido |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opções de carregamento |

### Valor de retorno

Apresentação lida

## IPresentationFactory::ReadPresentation(System::String) método

Lê uma apresentação existente a partir de um arquivo

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nome do arquivo |

### Valor de retorno

Apresentação lida

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) método

Lê uma apresentação existente a partir de um stream com opções de carregamento adicionais

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nome do arquivo |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opções de carregamento |

### Valor de retorno

Apresentação lida

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* classe [IPresentation](../../ipresentation/)
* classe [IPresentationFactory](../)
* classe [ILoadOptions](../../iloadoptions/)
* classe [Stream](../../../system.io/stream/)
* classe [String](../../../system/string/)
* namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)