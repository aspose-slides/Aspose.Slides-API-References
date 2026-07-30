---
title: GetNameValueLength()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte una stringa passata dall'indice specificato in un'istanza della classe NameValueHeaderValue.
type: docs
weight: 118
url: /it/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) metodo

Converte una stringa passata dall'indice specificato in un'istanza della classe [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una stringa da analizzare. |
| startIndex | **int32_t** | Una posizione di inizio per l'analisi. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Un'istanza in cui verrà assegnato un oggetto analizzato. |

### Valore di ritorno

Restituisce la lunghezza di una sottostringa analizzata, altrimenti 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) metodo

Converte una stringa passata dall'indice specificato in un'istanza della classe [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una stringa da analizzare. |
| startIndex | **int32_t** | Una posizione di inizio per l'analisi. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Una funzione utilizzata per creare nuove istanze della classe [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Un'istanza in cui verrà assegnato un oggetto analizzato. |

### Valore di ritorno

Restituisce la lunghezza di una sottostringa analizzata, altrimenti 0.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Classe [String](../../../system/string/)
* Classe [NameValueHeaderValue](../)
* Spazio dei nomi [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)