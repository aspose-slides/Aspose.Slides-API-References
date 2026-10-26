---
title: TestTools
second_title: Aspose.Slides için C++ API Referansı
description: Farklı tiplerin ve işlevlerin bazı temel özelliklerini kontrol eden bir dizi yararlı yöntem sağlar.
type: docs
weight: 1925
url: /tr/system/testtools/
---
## TestTools yapı

Farklı türlerin ve fonksiyonların bazı temel özelliklerini kontrol eden bir dizi yararlı yöntem sağlar.

```cpp
class TestTools
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Fonksiyonun herhangi bir türde istisna fırlatıp fırlatmadığını kontrol eder. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Dizgenin boş olup olmadığını kontrol eder. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Koleksiyonun boş olup olmadığını kontrol eder. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Belirli değerin null olup olmadığını kontrol eder. [Version](../version/) aritmetik ve enum tipleri için. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Belirli değerin null olup olmadığını kontrol eder. [Version](../version/) aritmetik olmayan ve enum olmayan değer tipleri için. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Belirli değerin null olup olmadığını kontrol eder. [Version](../version/) aritmetik olmayan değer tipleri için. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Belirli değerin null olup olmadığını kontrol eder. [Version](../version/) anahtar-değer çiftleri için. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Dizgenin null olup olmadığını kontrol eder. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Koleksiyonun null veya boş olup olmadığını kontrol eder. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Dizgenin null veya boş olup olmadığını kontrol eder. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)