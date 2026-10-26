---
title: ToString()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bayt dizisinin tüm değerlerini onaltılık dize temsiline dönüştürür. Onaltılık gösterimde kullanılacak harflerin büyük/küçük harf durumu ve komşu bayt çiftleri arasına eklenen ayırıcı, ilgili parametreler aracılığıyla belirtilir.
type: docs
weight: 157
url: /tr/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) metodu

Belirtilen bayt dizisinin tüm değerlerini onaltılık dize temsiline dönüştürür. Onaltılık gösterimde kullanılacak harflerin büyük/küçük harf durumu ve komşu bayt çiftleri arasına eklenen ayırıcı, ilgili parametreler aracılığıyla belirtilir.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) dönüştürülecek baytları içeren |
| uppercase | **bool** | Sonuçta oluşan onaltılık temsilde kullanılacak harflerin büyük/küçük harf durumunu belirtir |
| separator | const [String](../../string/)\& | Sonuç dizesinde komşu bayt çiftleri arasına eklenen ayırıcı olarak kullanılan bir dize |

### Dönüş Değeri

[String](../../string/) belirtilen bayt dizisinin onaltılık temsili

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) metodu

Belirtilen bayt dizisinin değerlerini, belirtilen dizinden başlayarak onaltılık dize temsiline dönüştürür.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) dönüştürülecek baytları içeren |
| startIndex | int | [Index](../../index/) belirtilen dizide dönüştürmeye başlanacak konum |

### Dönüş Değeri

[String](../../string/) belirtilen dizinin belirtilen eleman aralığının onaltılık temsili

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) metodu

Belirtilen bayt dizisinin bir aralık değerlerini onaltılık dize temsiline dönüştürür.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) dönüştürülecek baytları içeren |
| startIndex | int | [Index](../../index/) belirtilen dizide dönüştürülecek bayt dizisi elemanları aralığının başladığı konum |
| length | int | Dönüştürülecek bayt dizisi elemanları aralığının uzunluğu |

### Dönüş Değeri

[String](../../string/) belirtilen dizinin belirtilen eleman aralığının onaltılık temsili

## İlgili

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [String](../../string/)
* Sınıf [BitConverter](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)