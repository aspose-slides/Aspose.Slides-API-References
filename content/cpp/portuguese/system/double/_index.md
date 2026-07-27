---
title: Double
second_title: Referência da API Aspose.Slides para C++
description: Contém métodos para trabalhar com o número de ponto flutuante de dupla precisão.
type: docs
weight: 1574
url: /pt/system/double/
---
## Estrutura Double

Contém métodos para trabalhar com o número de ponto flutuante de dupla precisão.

```cpp
class Double
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente usando as informações de formatação fornecidas. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente usando as informações de formatação fornecidas e o estilo numérico. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente usando as informações de formatação fornecidas e o estilo numérico. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Campos

| Campo | Descrição |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Menor valor positivo que é maior que zero. |
| static constexpr [MaxValue](./maxvalue/) | Maior valor possível. |
| static constexpr [MinValue](./minvalue/) | Menor valor possível. |
| static constexpr [NaN](./nan/) | Valor que não é um número. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Infinito negativo. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Infinito positivo. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)