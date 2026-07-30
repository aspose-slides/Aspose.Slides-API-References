---
title: GetTransferCodingLength()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte una stringa passata dall'indice specificato in un'istanza della classe TransferCodingHeaderValue.
type: docs
weight: 105
url: /it/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) metodo

Converte una stringa passata dall'indice specificato in un'istanza della classe [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una stringa da analizzare. |
| startIndex | **int32_t** | Una posizione iniziale per l'analisi. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Un'istanza a cui verrà assegnato un oggetto analizzato. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | Il delegato usato per creare istanze della classe [TransferCodingHeaderValue](../). |

### Valore di ritorno

Restituisce la lunghezza di una sottostringa analizzata, altrimenti 0.

## Vedi anche

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Libreria [Aspose.Slides](../../../)