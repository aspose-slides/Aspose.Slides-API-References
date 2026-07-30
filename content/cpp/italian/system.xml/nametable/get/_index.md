---
title: Get()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la stringa atomizzata con il valore specificato.
type: docs
weight: 27
url: /it/system.xml/nametable/get/
---
## NameTable::Get(const String\&) metodo


Restituisce la stringa atomizzata con il valore specificato.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Il nome da trovare. |

### Valore di ritorno

L'oggetto stringa atomizzata o **nullptr** se la stringa non è già stata atomizzata.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metodo


Restituisce la stringa atomizzata contenente gli stessi caratteri dell'intervallo specificato di caratteri nell'array fornito.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | L'array di caratteri contenente il nome da trovare. |
| start | **int32_t** | L'indice basato su zero nell'array che specifica il primo carattere del nome. |
| len | **int32_t** | Il numero di caratteri nel nome. |

### Valore di ritorno

La stringa atomizzata o **nullptr** se la stringa non è già stata atomizzata. Se **len** è zero, viene restituito [String::Empty](../../../system/string/empty/).

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [NameTable](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)