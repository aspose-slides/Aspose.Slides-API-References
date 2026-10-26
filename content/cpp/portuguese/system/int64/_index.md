---
title: Int64
second_title: Referência da API do Aspose.Slides para C++
description: Contém métodos para trabalhar com o inteiro de 64 bits.
type: docs
weight: 1054
url: /pt/system/int64/
---
## Int64 classe

Contém métodos para trabalhar com o inteiro de 64 bits.

```cpp
class Int64
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&) | Converte a string especificada contendo a representação textual de um número ao inteiro assinado de 64 bits equivalente. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número ao inteiro assinado de 64 bits equivalente usando as informações de formatação fornecidas. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número ao inteiro assinado de 64 bits equivalente usando as informações de formatação e o estilo de número fornecidos. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int64_t**\&) | Converte a string especificada contendo a representação textual de um número ao inteiro assinado de 64 bits equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int64_t**\&) | Converte a string especificada contendo a representação textual de um número ao inteiro assinado de 64 bits equivalente usando as informações de formatação e o estilo de número fornecidos. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int64_t**\&) |  |

## Campos

| Campo | Descrição |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Maior valor possível. |
| static constexpr [MinValue](./minvalue/) | Menor valor possível. |

## Ver também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)