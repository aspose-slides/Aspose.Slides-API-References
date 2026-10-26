---
title: ToDouble()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen boolean değeri eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.
type: docs
weight: 222
url: /tr/system/convert/todouble/
---
## Convert::ToDouble(bool) yöntemi


Belirtilen boolean değeri eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) yöntemi


Belirtilen 8 bit işaretsiz tamsayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) yöntemi


Belirtilen 8 bit işaretli tamsayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) yöntemi


Belirtilen 16 bit işaretsiz tamsayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) yöntemi


Belirtilen 16 bit işaretli tamsayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) yöntemi


Belirtilen 32 bit işaretsiz tamsayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) yöntemi


Belirtilen 32 bit işaretli tamsayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) yöntemi


Belirtilen 64 bit işaretsiz tamsayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) yöntemi


Belirtilen 64 bit işaretli tamsayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) yöntemi


Belirtilen tek duyarlıklı sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) yöntemi


Belirtilen çift sayıyı döndürür.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) yöntemi


Belirtilen ondalık sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) yöntemi


Dönüştürme desteklenmiyor. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) yöntemi


Dönüştürme desteklenmiyor. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) yöntemi


Belirtilen null dizesini eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Dönüş Değeri

Sıfır.

## Convert::ToDouble(const char_t *) yöntemi


Bir sayının dize temsili içeren belirtilen c-dizgesini eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dizgesi |

### Dönüş Değeri

Belirtilen c-dizgesi tarafından temsil edilen sayıya eşit çift duyarlıklı kayan nokta değeri

## Convert::ToDouble(const String\&) yöntemi


Bir sayının dize temsili içeren belirtilen dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit çift duyarlıklı kayan nokta değeri

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) yöntemi


Sağlanan biçimlendirme bilgilerini kullanarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye gösterge |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit çift duyarlıklı kayan nokta değeri

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) yöntemi




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) yöntemi


Sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde bir kombinasyonu; sayının dize temsili için izin verilen stili belirtir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye gösterge |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit çift duyarlıklı kayan nokta değeri

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) yöntemi




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) yöntemi


Belirtilen kutulanmış değeri çift duyarlıklı kayan nokta değerine dönüştürür. Kutulanmış değerin türü [String](../../string/) ise, dönüştürme sırasında belirtilen dize biçimi kullanılır.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Değeri dönüştürmek için kutulayan nesneye ait paylaşımlı gösterge |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutulanmış değerin türü [String](../../string/) olduğunda kullanılacak dize biçimi |

### Dönüş Değeri

Belirtilen kutulanmış değere eşdeğer çift duyarlıklı kayan nokta değeri

## Bakınız

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