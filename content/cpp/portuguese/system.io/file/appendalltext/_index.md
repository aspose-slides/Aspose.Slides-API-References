---
title: AppendAllText()
second_title: Referência da API Aspose.Slides para C++
description: Anexa a string especificada ao arquivo especificado usando a codificação especificada.
type: docs
weight: 14
url: /pt/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) método

Anexa a string especificada ao arquivo especificado usando a codificação especificada.

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo ao qual a string será anexada |
| contents | const [String](../../../system/string/)\& | A string a ser escrita no arquivo |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação de caracteres a ser usada |

## Veja Também

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)