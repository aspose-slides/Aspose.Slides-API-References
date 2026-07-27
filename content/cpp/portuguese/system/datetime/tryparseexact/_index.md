---
title: TryParseExact()
second_title: Referência da API Aspose.Slides para C++
description: Converte a representação de string especificada de um valor de data e hora para o objeto DateTime equivalente usando o formato especificado, informações de formato específicas da cultura e o estilo. O formato da representação da string deve corresponder exatamente ao formato especificado.
type: docs
weight: 898
url: /pt/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) método


Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](../) equivalente usando o formato especificado, informações de formato específicas da cultura e o estilo. O formato da representação da string deve corresponder exatamente ao formato especificado.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação de string de um valor de data e hora a ser convertido. |
| format | const [String](../../string/)\& | O formato da string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O objeto [IFormatProvider](../../iformatprovider/) que fornece informações de formato específicas da cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Uma combinação bit a bit dos valores da enumeração que fornece informações adicionais sobre **s**, sobre elementos de estilo que podem estar presentes em **s**, ou sobre a conversão de **s** para um objeto [DateTime](../). |
| result | [DateTime](../)\& | O argumento de saída que, se a conversão for bem-sucedida, contém o resultado da conversão. |

### Valor de Retorno

Verdadeiro se a conversão for bem-sucedida, caso contrário - falso.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) método


Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](../) equivalente usando os formatos especificados, informações de formato específicas da cultura e o estilo. O formato da representação da string deve corresponder exatamente a um ou mais dos formatos especificados.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação de string de um valor de data e hora a ser convertido. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | O array de formatos de string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O objeto [IFormatProvider](../../iformatprovider/) que fornece informações de formato específicas da cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Uma combinação bit a bit dos valores da enumeração que fornece informações adicionais sobre **s**, sobre elementos de estilo que podem estar presentes em **s**, ou sobre a conversão de **s** para um objeto [DateTime](../). |
| result | [DateTime](../)\& | O argumento de saída que, se a conversão for bem-sucedida, contém o resultado da conversão. |

### Valor de Retorno

Verdadeiro se a conversão for bem-sucedida, caso contrário - falso.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) método




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Ver Também

* Enumeração [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [DateTime](../)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)