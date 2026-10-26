---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Atomizza la stringa specificata e la aggiunge al NameTable.
type: docs
weight: 14
url: /it/system.xml/nametable/add/
---
## NameTable::Add(const String\&) method

Atomizza la stringa specificata e la aggiunge a [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | La stringa da aggiungere. |

### Valore restituito

La stringa atomizzata o la stringa esistente se esiste già nel [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method

Atomizza la stringa specificata e la aggiunge a [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | L'array di caratteri contenente la stringa da aggiungere. |
| start | **int32_t** | L'indice base zero nell'array che specifica il primo carattere della stringa. |
| len | **int32_t** | Il numero di caratteri nella stringa. |

### Valore restituito

La stringa atomizzata o la stringa esistente se ne esiste già una nel [NameTable](../). Se **len** è zero, viene restituito [String::Empty](../../../system/string/empty/).

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [NameTable](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)