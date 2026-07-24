---
title: ToByte()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen boolean değerini eşdeğer bir 8 bit işaretsiz tam sayıya dönüştürür.
type: docs
weight: 92
url: /tr/system/convert/tobyte/
---
## Convert::ToByte(bool) metodu


Belirtilen bool değerini eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) metodu


Belirtilen 8 bit işaretsiz tamsayıyı döndürür.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) metodu


Belirtilen 8 bit işaretli tamsayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) metodu


Belirtilen 16 bit işaretsiz tamsayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) metodu


Belirtilen 16 bit işaretli tamsayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) metodu


Belirtilen 32 bit işaretsiz tamsayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) metodu


Belirtilen 32 bit işaretli tamsayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) metodu


Belirtilen 64 bit işaretsiz tamsayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) metodu


Belirtilen 64 bit işaretli tamsayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) metodu


Belirtilen float sayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) metodu


Belirtilen double sayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) metodu


Belirtilen ondalık sayıyı eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) metodu


Belirtilen Unicode karakterini eşdeğer bir 8 bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) metodu


Dönüştürme desteklenmez. Her zaman InvalidCastException hatası fırlatır.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) metodu


Belirtilen null dizesini eşdeğer 8 bit işaretsiz tamsayı değere dönüştürür.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```


### Dönüş Değeri

Sıfır.

## Convert::ToByte(const char_t *) metodu


Belirtilen c-dizesini, sayının dize temsiline göre eşdeğer 8 bit işaretsiz tamsayı değerine dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dizesi |

### Dönüş Değeri

Belirtilen c-dize tarafından temsil edilen sayıya eşit 8 bit işaretsiz tamsayı değeri

## Convert::ToByte(const String\&) metodu


Belirtilen dizeyi, sayının dize temsiline göre eşdeğer 8 bit işaretsiz tamsayı değerine dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretsiz tamsayı değeri

## Convert::ToByte(const String\&, int) metodu


Belirtilen dizeyi, belirtilen tabanda sayının dize temsiline göre eşdeğer 8 bit işaretsiz tamsayı değerine dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| from_base | int | Dizenin temsil ettiği sayının tabanı |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretsiz tamsayı değeri

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metodu


Sağlanan biçimlendirme bilgisi kullanılarak, belirtilen dizeyi sayının dize temsiline göre eşdeğer 8 bit işaretsiz tamsayı değerine dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize format bilgilerini içeren nesneye işaretçi |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretsiz tamsayı değeri

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) metodu




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodu


Sağlanan biçimlendirme bilgisi ve sayı stili kullanılarak, belirtilen dizeyi sayının dize temsiline göre eşdeğer 8 bit işaretsiz tamsayı değerine dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin izin verilen kombinasyonunu belirten bit tabanlı birleştirme |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize format bilgilerini içeren nesneye işaretçi |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretsiz tamsayı değeri

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metodu 




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) metodu 




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodu


Belirtilen kutulanmış değeri eşdeğer 8 bit işaretsiz tamsayı değerine dönüştürür.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Değeri dönüştürülecek nesneyi kutulayan paylaşımlı işaretçi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutulanmış değerin türü [String](../../string/) ise kullanılacak dize biçimi |

### Dönüş Değeri

Belirtilen kutulanmış değere eşdeğer 8 bit işaretsiz tamsayı değeri

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)