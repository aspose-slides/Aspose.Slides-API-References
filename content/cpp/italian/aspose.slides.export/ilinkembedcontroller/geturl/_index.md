---
title: GetUrl()
second_title: Riferimento API di Aspose.Slides per C++
description: "Restituisce un URL a un oggetto esterno. Questo metodo è sempre chiamato se ILinkEmbedController::GetObjectStoringLocation restituisce LinkEmbedDecision::Link e può essere chiamato se ILinkEmbedController::GetObjectStoringLocation restituisce LinkEmbedDecision::Embed ma l'incorporamento è impossibile. Può essere chiamato più volte per lo stesso ID oggetto."
type: docs
weight: 14
url: /it/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) metodo

Restituisce un URL a un oggetto esterno. Questo metodo è sempre chiamato se [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) restituisce [LinkEmbedDecision::Link](../../linkembeddecision/) e può essere chiamato se [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) restituisce [LinkEmbedDecision::Embed](../../linkembeddecision/) ma l'incorporamento è impossibile. Può essere chiamato più volte per lo stesso ID oggetto.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | **int32_t** | ID dell'oggetto. Questo ID è unico per l'intera operazione. |
| referrer | **int32_t** | ID dell'oggetto di riferimento o 0, se l'oggetto è referenziato dal documento radice. Può essere usato per generare un collegamento relativo. |

### Valore di ritorno

URL dell'oggetto esterno o null se questo oggetto deve essere ignorato.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)