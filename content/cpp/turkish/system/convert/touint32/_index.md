---
title: ToUInt32()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen boolean değeri eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.
type: docs
weight: 170
url: /tr/system/convert/touint32/
---
## Convert::ToUInt32(bool) metod

Belirtilen boolean değeri eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```
## Convert::ToUInt32(uint8_t) metod

Belirtilen 8 bitlik işaretsiz tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```
## Convert::ToUInt32(int8_t) metod

Belirtilen 8 bitlik işaretli tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```
## Convert::ToUInt32(uint16_t) metod

Belirtilen 16 bitlik işaretsiz tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```
## Convert::ToUInt32(int16_t) metod

Belirtilen 16 bitlik işaretli tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```
## Convert::ToUInt32(uint32_t) metod

Belirtilen 32 bit işaretsiz tam sayıyı döndürür.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```
## Convert::ToUInt32(int32_t) metod

Belirtilen 32 bit işaretli tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```
## Convert::ToUInt32(uint64_t) metod

Belirtilen 64 bitlik işaretsiz tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```
## Convert::ToUInt32(int64_t) metod

Belirtilen 64 bitlik işaretli tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```
## Convert::ToUInt32(float) metod

Belirtilen float sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```
## Convert::ToUInt32(double) metod

Belirtilen double sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```
## Convert::ToUInt32(const Decimal\&) metod

Belirtilen decimal sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```
## Convert::ToUInt32(char_t) metod

Belirtilen unicode karakteri eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```
## Convert::ToUInt32(DateTime) metod

Dönüştürme desteklenmez. Her zaman InvalidCastException hatası atar.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```
## Convert::ToUInt32(std::nullptr_t) metod

Belirtilen null dizesini eşdeğer işaretsiz 32 bit tam sayı değerine dönüştürür.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```


### Dönüş Değeri

Sıfır.

## Convert::ToUInt32(const char_t *) metod


Belirtilen sayının dize temsili içeren c-dizgesini eşdeğer işaretsiz 32 bit tam sayı değerine dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dizgesi |

### Dönüş Değeri

Belirtilen c-dizgesi tarafından temsil edilen sayıya eşit işaretsiz 32 bit tam sayı değeri

## Convert::ToUInt32(const String\&) metod


Belirtilen sayının dize temsili içeren dizeyi eşdeğer işaretsiz 32 bit tam sayı değerine dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit işaretsiz 32 bit tam sayı değeri

## Convert::ToUInt32(const String\&, int) metod


Belirtilen tabanda sayının dize temsili içeren dizeyi eşdeğer işaretsiz 32 bit tam sayı değerine dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| from_base | int | Dizgede temsil edilen sayının tabanı |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit işaretsiz 32 bit tam sayı değeri

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Belirtilen sayının dize temsili içeren dizeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer işaretsiz 32 bit tam sayı değerine dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize format bilgilerini içeren bir nesneye işaretçi |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit işaretsiz 32 bit tam sayı değeri

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) metod




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod


Belirtilen sayının dize temsili içeren dizeyi sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer işaretsiz 32 bit tam sayı değerine dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde birleştirilmesi ve sayının dize temsili için izin verilen stil |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize format bilgilerini içeren bir nesneye işaretçi |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit işaretsiz 32 bit tam sayı değeri

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metod




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) metod




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod

Belirtilen kutulanmış değeri eşdeğer işaretsiz 32 bit tam sayı değerine dönüştürür.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Değeri dönüştüren nesneyi kutulayan paylaşımlı işaretçi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutu değerinin türü [String](../../string/) ise kullanılacak dize formatı |

### Dönüş Değeri

Belirtilen kutulanmış değere eşdeğer işaretsiz 32 bit tam sayı değeri

## Ayrıca Bakınız

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