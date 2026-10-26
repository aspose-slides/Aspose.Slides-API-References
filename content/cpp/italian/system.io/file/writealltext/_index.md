---
title: WriteAllText()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo file di testo o sovrascrive quello esistente e scrive il contenuto della stringa specificata nel file utilizzando la codifica specificata.
type: docs
weight: 469
url: /it/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) metodo

Crea un nuovo file di testo o sovrascrive quello esistente e scrive il contenuto della stringa specificata nel file utilizzando la codifica specificata.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il file da creare o sovrascrivere |
| contents | const [String](../../../system/string/)\& | Un array di stringhe |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica dei caratteri da utilizzare |

## Vedi anche

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)