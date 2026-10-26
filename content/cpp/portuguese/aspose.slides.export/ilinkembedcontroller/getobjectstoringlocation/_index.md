---
title: GetObjectStoringLocation()
second_title: Aspose.Slides para C++ Referência da API
description: Determina onde o objeto deve ser armazenado. Este método é chamado uma vez para cada ID de objeto. Não há garantia de que não existam dois objetos com os mesmos dados, semanticName e contentType, mas com IDs diferentes.
type: docs
weight: 1
url: /pt/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) método


Determina onde o objeto deve ser armazenado. Este método é chamado uma vez para cada ID de objeto. Não há garantia de que não existam dois objetos com os mesmos dados, semanticName e contentType, mas com IDs diferentes.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | **int32_t** | ID do objeto. Esse ID é exclusivo em toda a operação de salvamento. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dados binários do objeto. Este parâmetro pode ser nulo, se os dados binários do objeto ainda não foram gerados. |
| semanticName | [System::String](../../../system/string/) | Um texto curto que descreve o significado do objeto. O controlador pode usar isso como parte do nome externo do objeto, mas cabe ao despachante garantir que os nomes sejam únicos e contenham apenas caracteres permitidos. |
| contentType | [System::String](../../../system/string/) | Tipo MIME do objeto. |
| recomendedExtension | [System::String](../../../system/string/) | Extensão de nome de arquivo recomendada para este tipo MIME. |

### Valor de Retorno

Decisão

## Veja Também

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)