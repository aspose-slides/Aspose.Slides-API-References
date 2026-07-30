---
title: ReadAllLines()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il contenuto del file di testo specificato riga per riga in un array di stringhe usando la codifica dei caratteri specificata.
type: docs
weight: 300
url: /it/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) metodo


Legge il contenuto del file di testo specificato riga per riga in un array di stringhe usando la codifica dei caratteri specificata.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file da leggere |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica dei caratteri da utilizzare |

### Valore di ritorno

Un array di stringhe, ciascun elemento dei quali rappresenta una singola riga del file specificato

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)