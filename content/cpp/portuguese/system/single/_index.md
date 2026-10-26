---
title: Single
second_title: Referência da API Aspose.Slides para C++
description: Contém métodos para trabalhar com o número de ponto flutuante de precisão simples.
type: docs
weight: 1899
url: /pt/system/single/
---
## Struct única

Contém métodos para trabalhar com o número de ponto flutuante de precisão simples.

```cpp
class Single
```

## Métodos

| Method | Descrição |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Converte a string especificada contendo a representação textual de um número para o valor de ponto flutuante de precisão simples equivalente. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o valor de ponto flutuante de precisão simples equivalente, usando as informações de formatação fornecidas. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o valor de ponto flutuante de precisão simples equivalente, usando as informações de formatação e o estilo de número fornecidos. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Converte a string especificada contendo a representação textual de um número para o valor de ponto flutuante de precisão simples equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Converte a string especificada contendo a representação textual de um número para o valor de ponto flutuante de precisão simples equivalente, usando as informações de formatação e o estilo de número fornecidos. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Campos

| Field | Descrição |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Menor valor positivo maior que zero. |
| static constexpr [MaxValue](./maxvalue/) | Maior valor possível. |
| static constexpr [MinValue](./minvalue/) | Menor valor possível. |
| static constexpr [NaN](./nan/) | Valor que não é um número. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Infinito negativo. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Infinito positivo. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)