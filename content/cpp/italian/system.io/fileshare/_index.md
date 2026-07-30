---
title: FileShare
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica quale tipo di accesso altri oggetti FileStream possono avere a un file aperto.
type: docs
weight: 534
url: /it/system.io/fileshare/
---
## FileShare enum

Specifica che tipo di accesso altri oggetti [FileStream](../filestream/) possono avere a un file aperto.

```cpp
enum class FileShare
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Nessun accesso. |
| Read | 1 | Accesso in sola lettura. |
| Write | 2 | Accesso in sola scrittura. |
| ReadWrite | 3 | Accesso di lettura e scrittura. |
| Delete | 4 | Il file può essere eliminato. |
| Inheritable | 16 | Rende l'handle del file ereditabile dai processi figli. |

## Vedi anche

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)