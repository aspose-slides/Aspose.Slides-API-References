---
title: ReadLines()
second_title: Riferimento API Aspose.Slides per C++
description: Legge il contenuto del file di testo specificato riga per riga usando la codifica dei caratteri specificata e restituisce una collezione enumerabile di stringhe, ognuna delle quali rappresenta una singola riga del contenuto del file.
type: docs
weight: 326
url: /it/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) metodo


Legge il contenuto del file di testo specificato riga per riga usando la codifica dei caratteri specificata e restituisce una collezione enumerabile di stringhe, ognuna delle quali rappresenta una singola riga del contenuto del file.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file da leggere |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica dei caratteri da utilizzare |

### Valore di ritorno

Una collezione enumerabile di stringhe che rappresenta il contenuto del file specificato

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)