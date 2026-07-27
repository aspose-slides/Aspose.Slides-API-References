---
title: WriteAllLines()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um novo arquivo de texto ou sobrescreve o existente e grava todas as strings da coleção enumerável especificada de strings nele, cada string em uma nova linha, usando a codificação especificada.
type: docs
weight: 456
url: /pt/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) método

Cria um novo arquivo de texto ou sobrescreve o existente e grava todas as strings da coleção enumerável especificada de strings nele, cada string em uma nova linha, usando a codificação especificada.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O arquivo a ser criado ou sobrescrito |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Uma coleção enumerável de strings |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação de caracteres a ser usada |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) método

Cria um novo arquivo de texto ou sobrescreve o existente e grava todas as strings do array de strings especificado nele, cada string em uma nova linha, usando a codificação especificada.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O arquivo a ser criado ou sobrescrito |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Um array de strings |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação de caracteres a ser usada |

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* classe [String](../../../system/string/)
* classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* classe [File](../)
* namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)