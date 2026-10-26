---
title: Get()
second_title: Riferimento API Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, restituisce la stringa atomizzata contenente gli stessi caratteri dell'intervallo specificato di caratteri nell'array fornito.
type: docs
weight: 1
url: /it/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metodo

Quando sovrascritto in una classe derivata, restituisce la stringa atomizzata contenente gli stessi caratteri dell'intervallo specificato di caratteri nell'array fornito.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | L'array di caratteri contenente il nome da cercare. |
| offset | **int32_t** | L'indice base-zero nell'array che specifica il primo carattere del nome. |
| length | **int32_t** | Il numero di caratteri nel nome. |

### Valore di ritorno

La stringa atomizzata o **nullptr** se la stringa non è già stata atomizzata. Se **length** è zero, viene restituito [String::Empty](../../../system/string/empty/).

## XmlNameTable::Get(const String\&) metodo

Quando sovrascritto in una classe derivata, restituisce la stringa atomizzata contenente lo stesso valore della stringa specificata.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Il nome da cercare. |

### Valore di ritorno

La stringa atomizzata o **nullptr** se la stringa non è già stata atomizzata.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)