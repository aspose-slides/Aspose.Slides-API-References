---
title: Parse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının string gösterimini içeren dizeyi eşdeğer 64-bit işaretli tamsayıya dönüştürür.
type: docs
weight: 1
url: /tr/system/int64/parse/
---
## Int64::Parse(const String\&) metodu

Belirtilen sayının string temsilini içeren dizeyi eşdeğer 64-bit işaretli tamsayıya dönüştürür.

```cpp
static int64_t System::Int64::Parse(const String &value)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit işaretli tamsayı.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metodu

Belirtilen sayının string temsilini içeren dizeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer 64-bit işaretli tamsayıya dönüştürür.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize formatı bilgisini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit işaretli tamsayı.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) metodu




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodu

Belirtilen sayının string temsilini içeren dizeyi sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer 64-bit işaretli tamsayıya dönüştürür.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bir sayının string temsilinin izin verilen stilini belirten NumberStyles enum değerlerinin bit düzeyinde bir kombinasyonu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize formatı bilgisini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit işaretli tamsayı.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metodu




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Ayrıca Bakınız

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Int64](../)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)