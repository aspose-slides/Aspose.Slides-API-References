---
title: Byte
second_title: Aspose.Slides för C++ API-referens
description: Innehåller metoder för att arbeta med det osignerade 8-bitars heltalet.
type: docs
weight: 157
url: /sv/system/byte/
---
## Byte-klass

Innehåller metoder för att arbeta med det osignerade 8-bitars heltalet.

```cpp
class Byte
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 8-bit-osignerade heltal. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 8-bit-osignerade heltal med den angivna formateringsinformationen. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 8-bit-osignerade heltal med den angivna formateringsinformationen och talstil. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint8_t**\&) | Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 8-bit-osignerade heltal. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint8_t**\&) | Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande 8-bit-osignerade heltal med den angivna formateringsinformationen och talstil. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint8_t**\&) |  |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Största möjliga värde. |
| static constexpr [MinValue](./minvalue/) | Minsta möjliga värde. |

## Anmärkningar



```cpp
#include <system/byte.h>

using namespace System;

int main()
{
  auto b1 = Byte::Parse(u"123");
  std::cout << static_cast<uint32_t>(b1) << std::endl;

  try
  {
    auto b2 = Byte::Parse(u"345");
    std::cout << static_cast<uint32_t>(b2) << std::endl;
  }
  catch (const OverflowException &ex)
  {
    std::cerr << ex.what() << std::endl;
  }

  uint8_t b3 = 0;
  if (Byte::TryParse(u"10", b3))
  {
    std::cout << static_cast<uint32_t>(b3) << std::endl;
  }
  else
  {
    std::cerr << "Something went wrong." << std::endl;
  }

  return 0;
}
/*
Det här kodexemplet producerar följande utskrift:
123
System::OverflowException: Värdet var antingen för stort eller för litet för en UInt8
10
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)