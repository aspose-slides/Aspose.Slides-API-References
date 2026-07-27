---
title: ParseExact()
second_title: Referência da API Aspose.Slides para C++
description: Converte string para objeto TimeSpan equivalente usando os formatos especificados, o provedor de formato e os estilos.
type: docs
weight: 547
url: /pt/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

Converte a string para o objeto [TimeSpan](../) equivalente usando os formatos especificados, o provedor de formato e os estilos.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | String de entrada. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) de strings de formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato que fornece informações de formatação específicas da cultura. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Define elementos que podem estar presentes na string de entrada. |

### Return Value

Intervalo de tempo que corresponde à string.

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

Converte a string para o objeto [TimeSpan](../) equivalente usando o formato especificado, o provedor de formato e os estilos.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | String de entrada. |
| format | const [String](../../string/)\& | String de formato padrão ou personalizado. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato que fornece informações de formatação específicas da cultura. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Define elementos que podem estar presentes na string de entrada. |

### Return Value

Intervalo de tempo que corresponde à string.

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Veja Também

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)