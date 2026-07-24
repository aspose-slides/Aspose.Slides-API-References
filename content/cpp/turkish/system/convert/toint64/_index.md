---
title: ToInt64()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen boolean değeri eşdeğer 64-bit işaretli tam sayıya dönüştürür.
type: docs
weight: 183
url: /tr/system/convert/toint64/
---
## Convert::ToInt64(bool) yöntemi


Belirtilen boolean değerini eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) yöntemi


Belirtilen 8-bit işaretsiz tam sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) yöntemi


Belirtilen 8-bit işaretli tam sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) yöntemi


Belirtilen 16-bit işaretsiz tam sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) yöntemi


Belirtilen 16-bit işaretli tam sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) yöntemi


Belirtilen 32-bit işaretsiz tam sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) yöntemi


Belirtilen 32-bit işaretli tam sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) yöntemi


Belirtilen 64-bit işaretsiz tam sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) yöntemi


Belirtilen 64-bit işaretli tam sayıyı döndürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) yöntemi


Belirtilen float sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) yöntemi


Belirtilen double sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) yöntemi


Belirtilen ondalık sayıyı eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) yöntemi


Belirtilen unicode karakterini eşdeğer 64-bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) yöntemi


Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) yöntemi


Belirtilen null-dizesini eşdeğer 64-bit tam sayı değerine dönüştürür.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```


### Dönüş Değeri

Sıfır.

## Convert::ToInt64(const char_t *) yöntemi


Belirtilen sayının dize temsili içeren c-dizesini eşdeğer 64-bit tam sayı değerine dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dize |

### Dönüş Değeri

Belirtilen c-dizesi tarafından temsil edilen sayıya eşit 64-bit tam sayı değeri

## Convert::ToInt64(const String\&) yöntemi


Belirtilen sayının dize temsili içeren dizeyi eşdeğer 64-bit tam sayı değerine dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit tam sayı değeri

## Convert::ToInt64(const String\&, int) yöntemi


Belirtilen sayının dize temsili içeren dizeyi belirtilen tabanda eşdeğer 64-bit tam sayı değerine dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| from_base | int | Dizenin temsil ettiği sayının tabanı |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit tam sayı değeri

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) yöntemi


Sağlanan biçimlendirme bilgilerini kullanarak belirtilen sayının dize temsili içeren dizeyi eşdeğer 64-bit tam sayı değerine dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim bilgilerini içeren nesneye işaretçi |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit tam sayı değeri

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) yöntemi




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) yöntemi


Sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak belirtilen sayının dize temsili içeren dizeyi eşdeğer 64-bit tam sayı değerine dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin, sayının dize temsili için izin verilen stilini belirten bit düzeyinde bir kombinasyonu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim bilgilerini içeren nesneye işaretçi |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 64-bit tam sayı değeri

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) yöntemi




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) yöntemi




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) yöntemi


Belirtilen kutulanmış değeri eşdeğer 64-bit tam sayı değerine dönüştürür.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Değeri dönüştürmek için kutulanmış nesneye işaretçi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutulanmış değerin tipi [String](../../string/) olduğunda kullanılacak dize formatı |

### Dönüş Değeri

Belirtilen kutulanmış değere eşdeğer 64-bit tam sayı değeri

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