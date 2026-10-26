---
title: GetEntity()
second_title: Referência da API Aspose.Slides para C++
description: Mapeia um URI para um objeto que contém o recurso real.
type: docs
weight: 14
url: /pt/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) método

Mapeia um URI para um objeto que contém o recurso real.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI absoluto para o objeto. |

### Valor de Retorno

Um objeto [System::IO::Stream](../../../system.io/stream/) ou nulo se o recurso não puder ser transmitido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Classe [ExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)