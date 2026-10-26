---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona legendas fechadas WebVTT ao final da coleção.
type: docs
weight: 27
url: /pt/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) método


Adiciona legendas fechadas WebVTT ao final da coleção.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | O rótulo das legendas fechadas. |
| filePath | [System::String](../../../system/string/) | O caminho para o arquivo WebVTT. |

### Valor de Retorno

A instância [ICaptions](../../icaptions/) adicionada.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) método


Adiciona legendas fechadas WebVTT ao final da coleção a partir de um fluxo.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | O rótulo das legendas fechadas. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | O fluxo de entrada contendo dados no formato WebVTT. |

### Valor de Retorno

A instância [ICaptions](../../icaptions/) adicionada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptions](../../icaptions/)
* Classe [String](../../../system/string/)
* Classe [ICaptionsCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)