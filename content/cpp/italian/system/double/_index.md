---
title: Double
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene metodi per lavorare con il numero a virgola mobile a doppia precisione.
type: docs
weight: 1574
url: /it/system/double/
---
## Struttura Double

Contiene metodi per lavorare con il numero a virgola mobile a doppia precisione.

```cpp
class Double
```

## Metodi

| Method | Description |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente utilizzando le informazioni di formattazione fornite. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Campi

| Field | Description |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Il più piccolo valore positivo maggiore di zero. |
| static constexpr [MaxValue](./maxvalue/) | Il valore più grande possibile. |
| static constexpr [MinValue](./minvalue/) | Il valore più piccolo possibile. |
| static constexpr [NaN](./nan/) | Valore che non è un numero. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Infinito negativo. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Infinito positivo. |

## Vedi anche

* Namespace [System](../)
* Library [Aspose.Slides](../../)