---
title: Single
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene metodi per lavorare con il numero a virgola mobile a precisione singola.
type: docs
weight: 1899
url: /it/system/single/
---
## Struttura singola

Contiene metodi per lavorare con il numero a virgola mobile a precisione singola.

```cpp
class Single
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente utilizzando le informazioni di formattazione fornite. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Campi

| Campo | Descrizione |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Il valore positivo più piccolo maggiore di zero. |
| static constexpr [MaxValue](./maxvalue/) | Il valore più grande possibile. |
| static constexpr [MinValue](./minvalue/) | Il valore più piccolo possibile. |
| static constexpr [NaN](./nan/) | Valore che non è un numero. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Infinito negativo. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Infinito positivo. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)