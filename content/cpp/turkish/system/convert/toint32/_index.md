---
title: ToInt32()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen boolean değeri eşdeğer 32-bit işaretli tam sayıya dönüştürür.
type: docs
weight: 157
url: /tr/system/convert/toint32/
---
## Convert::ToInt32(bool) metot

Belirtilen boolean değerini eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) metot

Belirtilen 8-bit işaretsiz tam sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) metot

Belirtilen 8-bit işaretli tam sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) metot

Belirtilen 16-bit işaretsiz tam sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) metot

Belirtilen 16-bit işaretli tam sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) metot

Belirtilen 32-bit işaretsiz tam sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) metot

Belirtilen 32-bit işaretli tam sayıyı döndürür.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) metot

Belirtilen 64-bit işaretsiz tam sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) metot

Belirtilen 64-bit işaretli tam sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) metot

Belirtilen float sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) metot

Belirtilen double sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) metot

Belirtilen decimal sayıyı eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) metot

Belirtilen unicode karakteri eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) metot

Dönüşüm desteklenmez. Her zaman InvalidCastException hatası fırlatır.

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) metot

Belirtilen null-dizgiyi eşdeğer 32-bit tam sayı değerine dönüştürür.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### Dönüş Değeri

Sıfır.

## Convert::ToInt32(const char_t *) metot

Bir sayının dize temsili içeren belirtilen c-dizgisini eşdeğer 32-bit tam sayı değerine dönüştürür.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dizgesi |

### Dönüş Değeri

Belirtilen c-dizgesi tarafından temsil edilen sayıya eşit 32-bit tam sayı değeri

## Convert::ToInt32(const String\&) metot

Bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 32-bit tam sayı değerine dönüştürür.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 32-bit tam sayı değeri

## Convert::ToInt32(const String\&, int) metot

Belirtilen tabanda bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 32-bit tam sayı değerine dönüştürür.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| from_base | int | Dizeyi temsil eden sayının tabanı |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 32-bit tam sayı değeri

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metot

Sağlanan biçimlendirme bilgilerini kullanarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 32-bit tam sayı değerine dönüştürür.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren nesneye işaretçi |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 32-bit tam sayı değeri

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metot

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metot

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) metot

```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metot

Sağlanan biçimlendirme bilgileri ve sayı stilini kullanarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 32-bit tam sayı değerine dönüştürür.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin izin verilen dize temsili stilini belirten bit düzeyi birleşimi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren nesneye işaretçi |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 32-bit tam sayı değeri

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metot

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metot

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metot

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) metot

```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metot

Belirtilen kutulanmış değeri eşdeğer 32-bit tam sayı değerine dönüştürür.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Dönüştürülecek değeri kutulayan nesneye ortak işaretçi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Eğer kutulmuş değerin türü [String](../../string/) ise kullanılacak dize biçimi |

### Dönüş Değeri

Belirtilen kutulanmış değere eşit 32-bit tam sayı değeri

## İlgili

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Decimal](../../decimal/)
* Sınıf [DateTime](../../datetime/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Sınıf [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Ad alanı [System](../../)
* Library [Aspose.Slides](../../../)