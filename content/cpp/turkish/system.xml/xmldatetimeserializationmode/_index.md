---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides için C++ API Referansı
description: Bir dizge ile DateTime arasında dönüşüm yapılırken zaman değerinin nasıl ele alınacağını belirtir.
type: docs
weight: 781
url: /tr/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

Bir dizge ile [DateTime](../../system/datetime/) arasında dönüşüm yapılırken zaman değerinin nasıl ele alınacağını belirtir.

```cpp
enum class XmlDateTimeSerializationMode
```

### Values

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Local | 0 | Yerel saat olarak ele alın. Eğer [DateTime](../../system/datetime/) nesnesi Koordinatlı Evrensel Zaman (UTC) temsil ediyorsa, yerel saate dönüştürülür. |
| Utc | 1 | UTC olarak ele alın. Eğer [DateTime](../../system/datetime/) nesnesi yerel saat temsil ediyorsa, UTC'ye dönüştürülür. |
| Unspecified | 2 | Bir [DateTime](../../system/datetime/) dizeye dönüştürülüyorsa yerel saat olarak ele alın. Bir dize [DateTime](../../system/datetime/)'e dönüştürülüyorsa, bir saat dilimi belirtilmişse yerel saate dönüştürün. |
| RoundtripKind | 3 | Dönüştürme sırasında saat dilimi bilgisi korunmalıdır. |

## Bakınız

* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)