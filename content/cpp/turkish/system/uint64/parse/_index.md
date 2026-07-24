---
title: Parse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsili içeren dizeyi eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.
type: docs
weight: 1
url: /tr/system/uint64/parse/
---
## UInt64::Parse(const String\&) yöntemi


Belirtilen sayının dize temsili içeren verilen dizeyi eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit işaretsiz tamsayı.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) yöntemi


Belirtilen sayının dize temsili içeren verilen dizeyi, sağlanan biçimlendirme bilgilerini kullanarak eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit işaretsiz tamsayı.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi



```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi



```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) yöntemi



```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) yöntemi


Belirtilen sayının dize temsili içeren verilen dizeyi, sağlanan biçimlendirme bilgileri ve sayı stilini kullanarak eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde birleştirilmesi; sayının dize temsili için izin verilen stili belirtir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit işaretsiz tamsayı.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi



```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi



```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) yöntemi



```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## İlgili

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)