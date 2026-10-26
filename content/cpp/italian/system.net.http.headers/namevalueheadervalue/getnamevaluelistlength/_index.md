---
title: GetNameValueListLength()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte una stringa fornita dall'indice specificato nella raccolta di istanze della classe NameValueHeaderValue e restituisce la lunghezza di una sottostringa analizzata.
type: docs
weight: 131
url: /it/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) metodo

Converte una stringa fornita dall'indice specificato nella raccolta di istanze della classe NameValueHeaderValue e restituisce la lunghezza di una sottostringa analizzata.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una stringa da analizzare. |
| startIndex | **int32_t** | Una posizione di inizio per l'analisi. |
| delimiter | char16_t | Una stringa usata per delimitare gli elementi nella stringa specificata. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Il parametro di output dove verrà assegnata una collezione analizzata. |

### Valore di ritorno

La lunghezza di una sottostringa analizzata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ObjectCollection](../../objectcollection/)
* Classe [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)