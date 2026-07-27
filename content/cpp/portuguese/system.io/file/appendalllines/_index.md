---
title: AppendAllLines()
second_title: Referência da API Aspose.Slides para C++
description: Anexa strings da coleção especificada de strings ao arquivo especificado usando a codificação especificada, escrevendo cada string em uma nova linha. Se o arquivo especificado não existir, ele será criado. O arquivo é fechado após a gravação de todas as strings.
type: docs
weight: 1
url: /pt/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method

Anexa strings da coleção especificada ao arquivo especificado usando a codificação especificada, escrevendo cada string em uma nova linha. Se o arquivo especificado não existir, ele será criado. O arquivo é fechado após a gravação de todas as strings.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo ao qual as strings serão anexadas |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | As strings a serem gravadas no arquivo |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação de caracteres a ser usada |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)