---
title: ToDateTime()
second_title: Aspose.Slides için C++ API Referansı
description: Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.
type: docs
weight: 248
url: /tr/system/convert/todatetime/
---
## Convert::ToDateTime(bool) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) metot


Dönüştürme desteklenmiyor. Her zaman InvalidCastException hatası atar.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) metot


Belirtilen tarih ve zamanı döndürür.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) metot


Belirtilen dizeyi [DateTime](../../datetime/) sınıfının bir örneğine dönüştürür.

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönüş Değeri

Belirtilen dizeyi, belirtilen dize tarafından temsil edilen tarih ve saat bilgilerini temsil eden [DateTime](../../datetime/) sınıfının bir örneğine dönüştürür.

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) metot


Belirtilen dizeyi sağlanan biçimlendirme bilgilerini kullanarak [DateTime](../../datetime/) sınıfının bir örneğine dönüştürür.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi |

### Dönüş Değeri

Belirtilen dizeyi, belirtilen dize tarafından temsil edilen tarih ve saat bilgilerini temsil eden [DateTime](../../datetime/) sınıfının bir örneğine dönüştürür.

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metot




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metot




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) metot




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metot


Belirtilen kutulanmış değeri eşdeğer [DateTime](../../datetime/) değerine dönüştürür.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Dönüştürülecek değeri kutulayan nesneye ortak işaretçi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutu değerinin türü [String](../../string/) olduğunda kullanılacak dize biçimi |

### Dönüş Değeri

[DateTime](../../datetime/) değeri, belirtilen kutulanmış değerle eşdeğerdir.

## Also See

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../../datetime/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)