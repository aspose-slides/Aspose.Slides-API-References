---
title: ReadAllText()
second_title: Riferimento API di Aspose.Slides for C++
description: Legge il contenuto del file di testo specificato in un unico oggetto String utilizzando la codifica dei caratteri specificata.
type: docs
weight: 313
url: /it/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) metodo

Legge il contenuto del file di testo specificato in un unico oggetto [String](../../../system/string/) utilizzando la codifica dei caratteri specificata.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file da leggere |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica dei caratteri da utilizzare |

### Valore di ritorno

Una stringa contenente il contenuto del file specificato

## Vedi anche

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)