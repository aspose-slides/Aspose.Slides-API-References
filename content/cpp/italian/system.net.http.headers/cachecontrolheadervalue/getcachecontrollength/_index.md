---
title: GetCacheControlLength()
second_title: Riferimento API Aspose.Slides per C++
description: Converte una stringa passata dall'indice specificato in un'istanza della classe CacheControlHeaderValue.
type: docs
weight: 456
url: /it/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) metodo

Converte una stringa passata dall'indice specificato in un'istanza della classe [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una stringa da analizzare. |
| startIndex | **int32_t** | Una posizione di avvio per l'analisi. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Un valore che deve essere aggiunto all'oggetto analizzato. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Un'istanza dove sarà assegnato un oggetto analizzato. |

### Valore di ritorno

La lunghezza di una sottostringa analizzata, altrimenti 0.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [CacheControlHeaderValue](../)
* Spazio dei nomi [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)