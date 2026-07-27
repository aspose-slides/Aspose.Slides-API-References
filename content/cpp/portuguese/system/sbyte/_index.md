---
title: SByte
second_title: Aspose.Slides para C++ Referência da API
description: Contém métodos para trabalhar com o inteiro de 8 bits.
type: docs
weight: 1873
url: /pt/system/sbyte/
---
## SByte struct

Contém métodos para trabalhar com o inteiro de 8 bits.

```cpp
class SByte
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 8 bits equivalente. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 8 bits equivalente usando as informações de formatação fornecidas. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 8 bits equivalente usando as informações de formatação e o estilo numérico fornecidos. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 8 bits equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 8 bits equivalente usando as informações de formatação e o estilo numérico fornecidos. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Campos

| Campo | Descrição |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Maior valor possível. |
| static constexpr [MinValue](./minvalue/) | Menor valor possível. |

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)