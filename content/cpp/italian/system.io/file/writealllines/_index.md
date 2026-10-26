---
title: WriteAllLines()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo file di testo o sovrascrive quello esistente e scrive tutte le stringhe dalla collezione enumerabile di stringhe specificata, ciascuna su una nuova riga, utilizzando la codifica specificata.
type: docs
weight: 456
url: /it/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method

Crea un nuovo file di testo o sovrascrive quello esistente e scrive tutte le stringhe dalla collezione enumerabile di stringhe specificata, ciascuna su una nuova riga, utilizzando la codifica specificata.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il file da creare o sovrascrivere |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Una collezione enumerabile di stringhe |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica dei caratteri da utilizzare |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) method

Crea un nuovo file di testo o sovrascrive quello esistente e scrive tutte le stringhe dall'array di stringhe specificato, ciascuna su una nuova riga, utilizzando la codifica specificata.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il file da creare o sovrascrivere |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Un array di stringhe |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica dei caratteri da utilizzare |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [File](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)