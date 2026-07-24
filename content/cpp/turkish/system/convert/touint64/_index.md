---
title: ToUInt64()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen boolean değeri eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.
type: docs
weight: 196
url: /tr/system/convert/touint64/
---
## Convert::ToUInt64(bool) metod

Belirtilen boolean değeri eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) metod

Belirtilen 8-bit işaretsiz tamsayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) metod

Belirtilen 8-bit işaretli tamsayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) metod

Belirtilen 16-bit işaretsiz tamsayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) metod

Belirtilen 16-bit işaretli tamsayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) metod

Belirtilen 32-bit işaretsiz tamsayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) metod

Belirtilen 32-bit işaretli tamsayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) metod

Belirtilen 64-bit işaretsiz tamsayıyı döndürür.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) metod

Belirtilen 64-bit işaretli tamsayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) metod

Belirtilen float sayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) metod

Belirtilen double sayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) metod

Belirtilen ondalık sayıyı eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) metod

Belirtilen unicode karakteri eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) metod

Dönüştürme desteklenmez. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) metod

Belirtilen null-dizgiyi eşdeğer işaretsiz 64-bit tamsayı değerine dönüştürür.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```


### Dönüş Değeri

Sıfır.

## Convert::ToUInt64(const char_t *) metod


Belirtilen sayının metin temsilini içeren c-dizgiyi eşdeğer işaretsiz 64-bit tamsayı değerine dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dizi |

### Dönüş Değeri

Belirtilen c-dizi tarafından temsil edilen sayıya eşit işaretsiz 64-bit tamsayı değeri

## Convert::ToUInt64(const String\&) metod


Belirtilen sayının metin temsilini içeren dizgeyi eşdeğer işaretsiz 64-bit tamsayı değerine dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dizge |

### Dönüş Değeri

Belirtilen dizge tarafından temsil edilen sayıya eşit işaretsiz 64-bit tamsayı değeri

## Convert::ToUInt64(const String\&, int) metod


Belirtilen tabanda sayının metin temsilini içeren dizgeyi eşdeğer işaretsiz 64-bit tamsayı değerine dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dizge |
| from_base | int | Dizge tarafından temsil edilen sayının tabanı |

### Dönüş Değeri

Belirtilen dizge tarafından temsil edilen sayıya eşit işaretsiz 64-bit tamsayı değeri

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Belirtilen sayının metin temsilini içeren dizgeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer işaretsiz 64-bit tamsayı değerine dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dizge |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dizge format bilgilerini içeren bir nesneye işaretçi |

### Dönüş Değeri

Belirtilen dizge tarafından temsil edilen sayıya eşit işaretsiz 64-bit tamsayı değeri

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod


Belirtilen sayının metin temsilini içeren dizgeyi sağlanan biçimlendirme bilgileri ve sayı stilini kullanarak eşdeğer işaretsiz 64-bit tamsayı değerine dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dizge |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin, sayının temsil biçimine izin verilen stilini belirten bit düzeyinde bir kombinasyonu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dizge format bilgilerini içeren bir nesneye işaretçi |

### Dönüş Değeri

Belirtilen dizge tarafından temsil edilen sayıya eşit işaretsiz 64-bit tamsayı değeri

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metod




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) metod




```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod


Belirtilen kutulanmış değeri eşdeğer işaretsiz 64-bit tamsayı değerine dönüştürür.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Dönüştürülecek değeri kutulayan nesneye işaret eden paylaşımlı gösterici |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutulanmış değerin tipi [String](../../string/) olduğunda kullanılacak dize biçimi |

### Dönüş Değeri

Belirtilen kutulanmış değere eşit işaretsiz 64-bit tamsayı değeri

## İlgili

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