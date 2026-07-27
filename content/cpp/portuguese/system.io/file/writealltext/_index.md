---
title: WriteAllText()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo arquivo de texto ou sobrescreve o existente e grava o conteúdo da string especificada nele usando a codificação especificada.
type: docs
weight: 469
url: /pt/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) método

Cria um novo arquivo de texto ou sobrescreve o existente e grava o conteúdo da string especificada nele usando a codificação especificada.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O arquivo a ser criado ou sobrescrito |
| contents | const [String](../../../system/string/)\& | Um array de strings |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação de caracteres a ser usada |

## Ver Também

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)