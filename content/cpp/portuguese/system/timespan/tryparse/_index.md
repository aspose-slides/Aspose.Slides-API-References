---
title: TryParse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string em um objeto TimeSpan equivalente e retorna o resultado da conversão.
type: docs
weight: 560
url: /pt/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) método


Converte a string em um objeto [TimeSpan](../) equivalente e retorna o resultado da conversão.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | String de entrada. |
| result | [TimeSpan](../)\& | Intervalo de tempo que corresponde à string. |

### Valor de retorno

Verdadeiro se a string foi convertida com sucesso; caso contrário, falso.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) método


Converte a string em um objeto [TimeSpan](../) equivalente usando o provedor de formato especificado e retorna o resultado da conversão.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | String de entrada. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato que fornece informações de formatação específicas da cultura. |
| result | [TimeSpan](../)\& | Intervalo de tempo que corresponde à string. |

### Valor de retorno

Verdadeiro se a string foi convertida com sucesso; caso contrário, falso.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) método




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) método




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) método




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Veja também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [TimeSpan](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)