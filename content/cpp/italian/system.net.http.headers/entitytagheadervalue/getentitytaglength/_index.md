---
title: GetEntityTagLength()
second_title: Riferimento API Aspose.Slides per C++
description: Converte una stringa passata dall'indice specificato in un'istanza della classe EntityTagHeaderValue.
type: docs
weight: 118
url: /it/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) metodo

Converte una stringa passata dall'indice specificato in un'istanza della classe [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una stringa da analizzare. |
| startIndex | **int32_t** | Una posizione di avvio per l'analisi. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Un'istanza in cui verrà assegnato un oggetto analizzato. |

### Valore di ritorno

La lunghezza di una sottostringa analizzata, altrimenti 0.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [EntityTagHeaderValue](../)
* Spazio dei nomi [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)