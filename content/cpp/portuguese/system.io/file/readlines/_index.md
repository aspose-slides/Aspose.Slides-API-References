---
title: ReadLines()
second_title: Referência da API Aspose.Slides para C++
description: Lê o conteúdo do arquivo de texto especificado linha por linha usando a codificação de caracteres especificada e retorna uma coleção enumerável de strings, cada uma representando uma única linha do conteúdo do arquivo.
type: docs
weight: 326
url: /pt/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) método

Lê o conteúdo do arquivo de texto especificado linha por linha usando a codificação de caracteres especificada e retorna uma coleção enumerável de strings, cada uma representando uma única linha do conteúdo do arquivo.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser lido |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação de caracteres a ser usada |

### Valor de Retorno

Uma coleção enumerável de strings que representam o conteúdo do arquivo especificado

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)