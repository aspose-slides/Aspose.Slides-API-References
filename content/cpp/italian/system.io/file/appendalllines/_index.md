---
title: AppendAllLines()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge stringhe dalla raccolta di stringhe specificata al file specificato usando la codifica specificata, scrivendo ogni stringa su una nuova riga. Se il file specificato non esiste, viene creato. Il file viene chiuso dopo aver scritto tutte le stringhe.
type: docs
weight: 1
url: /it/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metodo

Aggiunge stringhe dalla raccolta di stringhe specificata al file specificato usando la codifica specificata, scrivendo ogni stringa in una nuova riga. Se il file specificato non esiste, viene creato. Il file viene chiuso dopo aver scritto tutte le stringhe.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file a cui aggiungere le stringhe |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Le stringhe da scrivere nel file |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica dei caratteri da utilizzare |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [File](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)