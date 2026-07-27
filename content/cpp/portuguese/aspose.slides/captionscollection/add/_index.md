---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona legendas fechadas WebVTT ao final da coleção.
type: docs
weight: 27
url: /pt/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) método

Adiciona legendas fechadas WebVTT ao final da coleção.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | O rótulo das legendas fechadas. |
| filePath | [System::String](../../../system/string/) | O caminho para o arquivo WebVTT. |

### Valor de retorno

A instância [ICaptions](../../icaptions/) adicionada.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) método

Adiciona legendas fechadas WebVTT ao final da coleção a partir de um fluxo.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | O rótulo das legendas fechadas. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | O fluxo de entrada contendo dados no formato WebVTT. |

### Valor de retorno

A instância [ICaptions](../../icaptions/) adicionada.

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptions](../../icaptions/)
* Classe [String](../../../system/string/)
* Classe [CaptionsCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)