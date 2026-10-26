---
title: UInt32
second_title: Referência da API Aspose.Slides para C++
description: Contém métodos para trabalhar com o inteiro sem sinal de 32 bits.
type: docs
weight: 1977
url: /pt/system/uint32/
---
## UInt32 struct

Contém métodos para trabalhar com o inteiro sem sinal de 32 bits.

```cpp
class UInt32
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Converte a string especificada contendo a representação textual de um número para o inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o inteiro sem sinal de 32 bits equivalente usando as informações de formatação fornecidas. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o inteiro sem sinal de 32 bits equivalente usando as informações de formatação fornecidas e o estilo de número. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Converte a string especificada contendo a representação textual de um número para o inteiro sem sinal de 32 bits equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Converte a string especificada contendo a representação textual de um número para o inteiro sem sinal de 32 bits equivalente usando as informações de formatação fornecidas e o estilo de número. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Campos

| Campo | Descrição |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Maior valor possível. |
| static constexpr [MinValue](./minvalue/) | Menor valor possível. |

## Ver Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)