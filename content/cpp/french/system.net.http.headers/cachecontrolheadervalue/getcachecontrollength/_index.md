---
title: GetCacheControlLength()
second_title: Référence de l'API Aspose.Slides for C++
description: Convertit une chaîne passée depuis l'index spécifié en une instance de la classe CacheControlHeaderValue.
type: docs
weight: 456
url: /fr/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) méthode

Convertit une chaîne passée depuis l’index spécifié en une instance de la classe [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Une chaîne à analyser. |
| startIndex | **int32_t** | Une position de départ pour l’analyse. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Une valeur qui doit être ajoutée à l’objet analysé. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Une instance où un objet analysé sera attribué. |

### Valeur de retour

La longueur d’une sous-chaîne analysée, sinon 0.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [CacheControlHeaderValue](../)
* Espace de noms [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)