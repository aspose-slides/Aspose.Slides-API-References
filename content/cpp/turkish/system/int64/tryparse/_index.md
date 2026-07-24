---
title: TryParse()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen, bir sayının dize temsili içeren dizeyi eşdeğer 64 bit işaretli tamsayıya dönüştürür.
type: docs
weight: 14
url: /tr/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) metodu


Belirtilen, bir sayının dize temsili içeren dizeyi eşdeğer 64 bit işaretli tamsayıya dönüştürür.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| result | **int64_t**\& | Dönüşüm sonucunun konulduğu 64 bit işaretli tamsayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) metodu


Belirtilen, bir sayının dize temsili içeren dizeyi sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer 64 bit işaretli tamsayıya dönüştürür.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde birleşimi; bir sayının dize temsili için izin verilen stili belirtir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren nesneye bir işaretçi. |
| result | **int64_t**\& | Dönüşüm sonucunun konulduğu 64 bit işaretli tamsayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) metodu




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) metodu




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) metodu




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Ayrıca

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Int64](../)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Ad Alanı [System](../../)
* Library [Aspose.Slides](../../../)