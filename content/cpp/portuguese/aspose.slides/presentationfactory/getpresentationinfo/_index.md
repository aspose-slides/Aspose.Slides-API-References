---
title: GetPresentationInfo()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo objeto PresentationInfo a partir de um arquivo e vincula a apresentação a ele.
type: docs
weight: 27
url: /pt/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) método

Cria um novo objeto [PresentationInfo](../../presentationinfo/) a partir do arquivo e vincula a apresentação a ele.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) arquivo. |

### Valor de Retorno

[Presentation](../../presentation/) informação vinculada à apresentação.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) método

Cria um novo objeto [PresentationInfo](../../presentationinfo/) a partir do fluxo e vincula a apresentação a ele. Obtém informações sobre a apresentação no fluxo especificado.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) fluxo. |

### Valor de Retorno

[Presentation](../../presentation/) informação vinculada à apresentação.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationInfo](../../ipresentationinfo/)
* Classe [String](../../../system/string/)
* Classe [PresentationFactory](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)