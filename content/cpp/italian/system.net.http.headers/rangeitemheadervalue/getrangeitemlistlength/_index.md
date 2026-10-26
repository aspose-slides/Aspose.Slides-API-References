---
title: GetRangeItemListLength()
second_title: Riferimento API Aspose.Slides per C++
description: Converte una stringa passata dalla posizione specificata nella collezione di istanze della classe RangeItemHeaderValue.
type: docs
weight: 79
url: /it/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) metodo

Converte una stringa passata dalla posizione specificata nella collezione di istanze della classe RangeItemHeaderValue.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una stringa da analizzare. |
| startIndex | **int32_t** | Una posizione di partenza per l'analisi. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Un'istanza dove verrà assegnata una collezione analizzata. |

### Valore di ritorno

La lunghezza di una sottostringa analizzata, altrimenti 0.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ICollection](../../../system.collections.generic/icollection/)
* Classe [RangeItemHeaderValue](../)
* Spazio dei nomi [System::Net::Http::Headers](../../)
* Libreria [Aspose.Slides](../../../)