---
title: Hyperlink()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma instância de um hyperlink.
type: docs
weight: 339
url: /pt/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) construtor

Cria uma instância de um hyperlink.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) construtor

Cria uma instância de um hyperlink que aponta para um slide específico. Observação: o hyperlink criado deve ser atribuído a algum objeto da mesma apresentação, caso contrário o link será salvo como NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Slide de destino. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) construtor

Cria uma instância de um hyperlink usando outro hyperlink como origem, sobrescrevendo propriedades secundárias.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Hyperlink de origem |
| targetFrame | [System::String](../../../system/string/) | Quadro de destino |
| tooltip | [System::String](../../../system/string/) | Texto da dica |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Hyperlink](../)
* Classe [ISlide](../../islide/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)