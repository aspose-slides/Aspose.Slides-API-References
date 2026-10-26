---
title: ToSingle()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen boolean değeri eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.
type: docs
weight: 209
url: /tr/system/convert/tosingle/
---
## Convert::ToSingle(bool) metod

Belirtilen boolean değerini eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) metod

Belirtilen 8 bitlik işaretsiz tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) metod

Belirtilen 8 bitlik işaretli tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) metod

Belirtilen 16 bitlik işaretsiz tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) metod

Belirtilen 16 bitlik işaretli tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) metod

Belirtilen 32 bitlik işaretsiz tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) metod

Belirtilen 32 bitlik işaretli tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) metod

Belirtilen 64 bitlik işaretsiz tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) metod

Belirtilen 64 bitlik işaretli tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) metod

Belirtilen float sayıyı döndürür.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) metod

Belirtilen double değerini eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) metod

Belirtilen decimal sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) metod

Dönüştürme desteklenmez. Her zaman InvalidCastException hatası atar.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) metod

Dönüştürme desteklenmez. Her zaman InvalidCastException hatası atar.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) metod

Belirtilen null-string değerini eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```


### Return Value

Sıfır.

## Convert::ToSingle(const char_t *) metod

Belirtilen sayının dize temsili içeren c-dizgisini eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dizi |

### Return Value

Belirtilen c-dizgi tarafından temsil edilen sayıya eşit tek duyarlıklı kayan nokta değeri

## Convert::ToSingle(const String\&) metod


Belirtilen sayının dize temsili içeren stringi eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static float System::Convert::ToSingle(const String &value)
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek string |

### Return Value

Belirtilen string tarafından temsil edilen sayıya eşit tek duyarlıklı kayan nokta değeri

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Belirtilen sayının dize temsili içeren stringi, verilen biçimlendirme bilgisi kullanılarak eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek string |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | String formatı bilgisini içeren nesneye işaretçi |

### Return Value

Belirtilen string tarafından temsil edilen sayıya eşit tek duyarlıklı kayan nokta değeri

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) metod




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod


Belirtilen sayının dize temsili içeren stringi, verilen biçimlendirme bilgisi ve sayı stili kullanılarak eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek string |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bitwise birleşimi; bir sayının dize temsili için izin verilen stili belirler |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | String formatı bilgisini içeren nesneye işaretçi |

### Return Value

Belirtilen string tarafından temsil edilen sayıya eşit tek duyarlıklı kayan nokta değeri

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) metod




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod


Belirtilen kutulanmış değeri tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Değeri dönüştürmek için kutulayan nesneye yönelik paylaşımlı işaretçi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutulanan değerin türü [String](../../string/) ise kullanılacak string formatı |

### Return Value

Belirtilen kutulanmış değere eşit tek duyarlıklı kayan nokta değeri

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)