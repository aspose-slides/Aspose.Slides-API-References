---
title: GetUrl()
second_title: Referencia de API de Aspose.Slides para C++
description: "Devuelve una URL a un objeto externo. Este método siempre se llama si ILinkEmbedController::GetObjectStoringLocation devuelve LinkEmbedDecision::Link y puede llamarse si ILinkEmbedController::GetObjectStoringLocation devuelve LinkEmbedDecision::Embed pero la incrustación es imposible. Puede llamarse varias veces para el mismo id de objeto."
type: docs
weight: 14
url: /es/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) método


Returns an URL to an external object. This method always called if [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) returned [LinkEmbedDecision::Link](../../linkembeddecision/) and may be called if [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) returned [LinkEmbedDecision::Embed](../../linkembeddecision/) but embedding is impossible. Can be called multiple time for same object id.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | **int32_t** | Identificador del objeto. Este identificador es único en toda la operación. |
| referrer | **int32_t** | Identificador del objeto de referencia o 0, si el objeto es referenciado por el documento raíz. Puede usarse para generar un enlace relativo. |

### Valor devuelto

Url del objeto externo o null si este objeto debe ser ignorado.

## Véase también

* Clase [String](../../../system/string/)
* Clase [ILinkEmbedController](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)