---
title: GetMediaTypeLength()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte una stringa passata dall'indice specificato in un'istanza della classe MediaTypeHeaderValue.
type: docs
weight: 144
url: /it/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) metodo

Converte una stringa passata dall'indice specificato in un'istanza della classe [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una stringa da analizzare. |
| startIndex | **int32_t** | Una posizione iniziale per l'analisi. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | Il delegato utilizzato per creare istanze della classe [MediaTypeHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Un'istanza dove verrà assegnato un oggetto analizzato. |

### Valore di ritorno

Restituisce la lunghezza di una sottostringa analizzata, altrimenti 0.

## Vedi anche

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [MediaTypeHeaderValue](../)
* Spazio dei nomi [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)