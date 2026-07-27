---
title: ParseExact()
second_title: Referência da API Aspose.Slides para C++
description: Converte a representação em string especificada de um valor de data e hora para o objeto DateTime equivalente usando o formato especificado e as informações de formato específicas da cultura. O formato da representação em string deve corresponder exatamente ao formato especificado. Lança uma exceção se a conversão falhar.
type: docs
weight: 872
url: /pt/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) método

Converte a representação em string especificada de um valor de data e hora para o objeto [DateTime](../) equivalente usando o formato especificado e as informações de formato específicas da cultura. O formato da representação em string deve corresponder exatamente ao formato especificado. Lança uma exceção se a conversão falhar.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um valor de data e hora a ser convertido. |
| format | const [String](../../string/)\& | O formato da string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O objeto [IFormatProvider](../../iformatprovider/) que fornece informações de formato específicas da cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Uma combinação bit a bit dos valores da enumeração que fornece informações adicionais sobre **s**, sobre elementos de estilo que podem estar presentes em **s**, ou sobre a conversão de **s** para um objeto [DateTime](../). |

### Valor de Retorno

Uma nova instância da classe [DateTime](../) que representa o valor de data e hora equivalente ao representado pela string especificada.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) método

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) método

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) método

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) método

Converte a representação em string especificada de um valor de data e hora para o objeto [DateTime](../) equivalente usando os formatos especificados, as informações de formato específicas da cultura e o estilo. O formato da representação em string deve corresponder exatamente a um ou mais dos formatos especificados. Lança uma exceção se a conversão falhar.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um valor de data e hora a ser convertido. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | O array de formatos de string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O objeto [IFormatProvider](../../iformatprovider/) que fornece informações de formato específicas da cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Uma combinação bit a bit dos valores da enumeração que fornece informações adicionais sobre **s**, sobre elementos de estilo que podem estar presentes em **s**, ou sobre a conversão de **s** para um objeto [DateTime](../). |

### Valor de Retorno

Uma nova instância da classe [DateTime](../) que representa o valor de data e hora equivalente ao representado pela string especificada.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) método

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) método

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) método

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Veja Também

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)