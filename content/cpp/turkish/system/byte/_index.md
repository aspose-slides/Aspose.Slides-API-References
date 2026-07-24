---
title: Byte
second_title: Aspose.Slides for C++ API Referansı
description: İşaretsiz 8-bit tam sayı ile çalışmak için yöntemler içerir.
type: docs
weight: 157
url: /tr/system/byte/
---
## Byte sınıfı


İşaretsiz 8-bit tam sayı ile çalışmak için yöntemler içerir.

```cpp
class Byte
```

## Methods

| Yöntem | Açıklama |
| --- | --- |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&) | Belirtilen sayının dize temsilini içeren dizeyi eşdeğer 8-bit işaretsiz tam sayıya dönüştürür. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsilini içeren dizeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer 8-bit işaretsiz tam sayıya dönüştürür. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsilini içeren dizeyi sağlanan biçimlendirme bilgileri ve sayı biçimi kullanarak eşdeğer 8-bit işaretsiz tam sayıya dönüştürür. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint8_t**\&) | Belirtilen sayının dize temsilini içeren dizeyi eşdeğer 8-bit işaretsiz tam sayıya dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint8_t**\&) | Belirtilen sayının dize temsilini içeren dizeyi sağlanan biçimlendirme bilgileri ve sayı biçimi kullanarak eşdeğer 8-bit işaretsiz tam sayıya dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint8_t**\&) |  |

## Fields

| Alan | Açıklama |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Olabilecek en büyük değer. |
| static constexpr [MinValue](./minvalue/) | Olabilecek en küçük değer. |

## Açıklamalar



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
Bu kod örneği aşağıdaki çıktıyı üretir:
123
System::OverflowException: Değer ya çok büyük ya da UInt8 için çok küçüktü
10
*/
```

## Diğer Bağlantılar

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)