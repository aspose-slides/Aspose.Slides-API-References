---
title: ReadAllLines()
second_title: Referência da API Aspose.Slides para C++
description: Lê o conteúdo do arquivo de texto especificado linha a linha para um array de strings usando a codificação de caracteres especificada.
type: docs
weight: 300
url: /pt/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) método

Lê o conteúdo do arquivo de texto especificado linha a linha para um array de strings usando a codificação de caracteres especificada.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser lido |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação de caracteres a ser usada |

### Valor de Retorno

Um array de strings onde cada elemento representa uma única linha do arquivo especificado

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)