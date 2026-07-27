---
title: TryParseExact()
second_title: Referência da API Aspose.Slides para C++
description: Tenta converter a string especificada para o objeto DateTimeOffset usando os formatos especificados, o provedor de formato e o estilo de formatação.
type: docs
weight: 742
url: /pt/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) método


Tenta converter a string especificada para o objeto [DateTimeOffset](../) usando os formatos especificados, o provedor de formato e o estilo de formatação.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) a converter. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Matrizes de strings de formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formatação de data e hora. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) que é equivalente ao **input**. |

### Return Value

true se o **input** for convertido com sucesso, caso contrário - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) método


Tenta converter a string especificada para o objeto [DateTimeOffset](../) usando o formato especificado, o provedor de formato e o estilo de formatação.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) a converter. |
| format | const [String](../../string/)\& | String de formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formatação de data e hora. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) que é equivalente ao **input**. |

### Return Value

true se o **input** for convertido com sucesso, caso contrário - false.

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [DateTimeOffset](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)