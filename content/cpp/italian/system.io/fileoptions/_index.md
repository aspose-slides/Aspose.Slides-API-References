---
title: FileOptions
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le opzioni avanzate per creare l'oggetto FileStream.
type: docs
weight: 521
url: /it/system.io/fileoptions/
---
## FileOptions enum

Rappresenta le opzioni avanzate per creare l'oggetto [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### Valori

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Nessuna opzione aggiuntiva. |
| Encrypted | 16384 | Il file è crittografato. NON IMPLEMENTATO. |
| DeleteOnClose | 67108864 | Il file dovrebbe essere eliminato automaticamente quando non è più in uso. |
| SequentialScan | 134217728 | Il file dovrebbe essere accessibile in modo sequenziale. |
| RandomAccess | 268435456 | Il file è accessibile in modo casuale. |
| Asynchronous | 1073741824 | Il file può essere usato per operazioni I/O asincrone. |
| WriteThrough | n/a | Tutte le scritture dovrebbero andare direttamente sul disco bypassando qualsiasi cache intermedia. |

## Vedi anche

* Namespace [System::IO](../)
* Libreria [Aspose.Slides](../../)