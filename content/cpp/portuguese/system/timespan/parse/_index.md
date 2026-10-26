---
title: Parse()
second_title: Referência da API Aspose.Slides para C++
description: Converte string para o objeto TimeSpan equivalente.
type: docs
weight: 534
url: /pt/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) method


Converte a string para o objeto [TimeSpan](../) equivalente.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | String de entrada. |

### Valor de Retorno

Intervalo de tempo que corresponde à string.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converte a string para o objeto [TimeSpan](../) equivalente usando o provedor de formato especificado.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | String de entrada. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato que fornece informações de formatação específicas da cultura. |

### Valor de Retorno

Intervalo de tempo que corresponde à string.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [TimeSpan](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)