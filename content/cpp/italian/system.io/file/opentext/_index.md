---
title: OpenText()
second_title: Aspose.Slides per C++ Riferimento API
description: Apre il file esistente specificato per leggere testo usando la codifica UTF-8 senza condivisione.
type: docs
weight: 261
url: /it/system.io/file/opentext/
---
## File::OpenText(const String&, const EncodingPtr&) metodo

Apre il file esistente specificato per leggere testo usando la codifica UTF-8 senza condivisione.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Il percorso del file da aprire |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | La codifica dei caratteri da utilizzare |

### Valore di ritorno

Un puntatore condiviso a un oggetto [StreamWriter](../../streamwriter/) associato al file aperto

## Vedi anche

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)