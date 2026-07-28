---
title: Byte
second_title: Aspose.Slides C++ API hivatkozás
description: Metódusokat tartalmaz a nem előjeles 8 bites egész számmal való munkához.
type: docs
weight: 157
url: /hu/system/byte/
---
## Byte osztály

Metódusokat tartalmaz a nem előjeles 8 bites egész szám kezeléséhez.

```cpp
class Byte
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott, egy szám sztring reprezentációját tartalmazó karakterláncot az ekvivalens 8 bites nem előjeles egész számmá. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott, egy szám sztring reprezentációját tartalmazó karakterláncot az ekvivalens 8 bites nem előjeles egész számmá a megadott formázási információk felhasználásával. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a megadott, egy szám sztring reprezentációját tartalmazó karakterláncot az ekvivalens 8 bites nem előjeles egész számmá a megadott formázási információk és számstílus felhasználásával. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint8_t**\&) | Átalakítja a megadott, egy szám sztring reprezentációját tartalmazó karakterláncot az ekvivalens 8 bites nem előjeles egész számmá. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint8_t**\&) | Átalakítja a megadott, egy szám sztring reprezentációját tartalmazó karakterláncot az ekvivalens 8 bites nem előjeles egész számmá a megadott formázási információk és számstílus felhasználásával. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint8_t**\&) |  |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Legnagyobb lehetséges érték. |
| static constexpr [MinValue](./minvalue/) | Legkisebb lehetséges érték. |

## Megjegyzések



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
Ez a kódpélda a következő kimenetet állítja elő:
123
System::OverflowException: Az érték vagy túl nagy, vagy túl kicsi egy UInt8 típushoz
10
*/
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)