---
title: Guid
second_title: Aspose.Slides for C++ API Referansı
description: "Küresel Benzersiz Tanımlayıcıyı temsil eder. Bu tip yığında tahsis edilmeli ve fonksiyonlara değer olarak veya referansla aktarılmalıdır. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 885
url: /tr/system/guid/
---
## Guid sınıfı

Küresel Benzersiz Tanımlayıcıyı (GUID) temsil eder. Bu tip yığında tahsis edilmeli ve fonksiyonlara değer olarak veya referansla aktarılmalıdır. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Guid
```

## Yöntemler

| Method | Description |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen GUID'lerin aritmetik karşılaştırmasını yapar. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen GUID'lerin eşit olup olmadığını belirler. |
| int [GetHashCode](./gethashcode/)() const | Geçerli nesne için bir hash kodu döndürür. |
| [Guid](./guid/)() | Tüm sıfırlardan oluşan bir GUID temsil eden bir nesne oluşturur. |
| [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Unsigned 8-bit tam sayı değerleri dizisi olarak belirtilen bir GUID'yi temsil eden bir nesne oluşturur. |
| [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Unsigned 8-bit tam sayı değerlerinin dizi görünümü olarak belirtilen bir GUID'yi temsil eden bir nesne oluşturur. |
| [Guid](./guid/)(const [String](../string/)\&) | Bir dize olarak belirtilen bir GUID'yi temsil eden bir nesne oluşturur. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Belirtilen GUID bileşenlerinden [Guid](./) sınıfının bir örneğini oluşturur. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Belirtilen GUID bileşenlerinden [Guid](./) sınıfının bir örneğini oluşturur. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Belirtilen unsigned tamsayılar ve baytlardan [Guid](./) sınıfının bir örneğini oluşturur. |
| [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Belirtilen unsigned tamsayılar ve baytlardan [Guid](./) sınıfının bir örneğini oluşturur. |
| [Guid](./guid/)(const [Guid](./)\&) | Belirtilen nesneyle aynı GUID'yi temsil eden bir nesne oluşturur. |
| static [Guid](./) [NewGuid](./newguid/)() | Yeni bir GUID üretir ve onu temsil eden bir [Guid](./) nesnesi döndürür. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen GUID'lerin eşit olmama durumunu belirler. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Geçerli nesneye, belirtilen [Guid](./) nesnesi tarafından temsil edilen GUID değerini atar. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen GUID'lerin eşit olup olmadığını belirler. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Belirtilen GUID dize temsilini eşdeğer bir [Guid](./) nesnesine dönüştürür. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Geçerli nesne tarafından temsil edilen GUID'yi bayt dizisine dönüştürür. |
| [String](../string/) [ToString](./tostring/)() const | Geçerli nesne tarafından temsil edilen GUID'yi dize temsiline dönüştürür. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Geçerli nesne tarafından temsil edilen GUID'yi belirtilen dize biçimini kullanarak dize temsiline dönüştürür. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Geçerli nesne tarafından temsil edilen GUID'yi belirtilen dize biçimi ve Culture kullanarak dize temsiline dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Belirtilen dizeyi [Guid](./) nesnesine dönüştürmeye çalışır. |
| [~Guid](./~guid/)() | Yıkıcı. |

## Alanlar

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Değeri 0 olan bir GUID'yi temsil eder. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)