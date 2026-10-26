---
title: ReadAllText()
second_title: Referência da API Aspose.Slides para C++
description: Lê o conteúdo do arquivo de texto especificado para um único objeto String usando a codificação de caracteres especificada.
type: docs
weight: 313
url: /pt/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) método

Lê o conteúdo do arquivo de texto especificado para um único objeto [String](../../../system/string/) usando a codificação de caracteres especificada.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser lido |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação de caracteres a ser usada |

### Valor de Retorno

Uma string contendo o conteúdo do arquivo especificado

## Ver Também

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)