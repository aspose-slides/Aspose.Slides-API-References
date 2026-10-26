---
title: OpenText()
second_title: Referência da API Aspose.Slides para C++
description: Abre o arquivo existente especificado para leitura de texto usando codificação UTF-8 sem compartilhamento.
type: docs
weight: 261
url: /pt/system.io/file/opentext/
---
## File::OpenText(const String&, const EncodingPtr&) método

Abre o arquivo existente especificado para leitura de texto usando codificação UTF-8 sem compartilhamento.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser aberto |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação de caracteres a ser usada |

### Valor de Retorno

Um ponteiro compartilhado para um objeto [StreamWriter](../../streamwriter/) associado ao arquivo aberto

## Ver Também

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)