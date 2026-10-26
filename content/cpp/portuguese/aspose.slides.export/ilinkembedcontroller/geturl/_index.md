---
title: GetUrl()
second_title: Referência da API Aspose.Slides para C++
description: "Retorna uma URL para um objeto externo. Este método sempre é chamado se ILinkEmbedController::GetObjectStoringLocation retornou LinkEmbedDecision::Link e pode ser chamado se ILinkEmbedController::GetObjectStoringLocation retornou LinkEmbedDecision::Embed, mas a incorporação é impossível. Pode ser chamado várias vezes para o mesmo id de objeto."
type: docs
weight: 14
url: /pt/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) método

Retorna uma URL para um objeto externo. Este método sempre é chamado se [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) retornou [LinkEmbedDecision::Link](../../linkembeddecision/) e pode ser chamado se [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) retornou [LinkEmbedDecision::Embed](../../linkembeddecision/) mas a incorporação é impossível. Pode ser chamado várias vezes para o mesmo id de objeto.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | **int32_t** | ID do objeto. Este ID é único em toda a operação. |
| referrer | **int32_t** | ID do objeto referenciador ou 0, se o objeto for referenciado pelo documento raiz. Pode ser usado para gerar link relativo. |

### Valor de Retorno

URL do objeto externo ou null se este objeto deve ser ignorado.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [ILinkEmbedController](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)