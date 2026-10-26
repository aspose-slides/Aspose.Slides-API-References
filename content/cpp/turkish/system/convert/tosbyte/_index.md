---
title: ToSByte()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen boolean değeri eşdeğer 8-bit işaretli tam sayıya dönüştürür.
type: docs
weight: 105
url: /tr/system/convert/tosbyte/
---
## Convert::ToSByte(bool) metodu


Belirtilen boolean değeri eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) metodu


Belirtilen 8 bit işaretsiz tam sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) metodu


Belirtilen 8 bit işaretli tam sayıyı döndürür.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) metodu


Belirtilen 16 bit işaretsiz tam sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) metodu


Belirtilen 16 bit işaretli tam sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) metodu


Belirtilen 32 bit işaretsiz tam sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) metodu


Belirtilen 32 bit işaretli tam sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) metodu


Belirtilen 64 bit işaretsiz tam sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) metodu


Belirtilen 64 bit işaretli tam sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) metodu


Belirtilen float sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) metodu


Belirtilen double sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) metodu


Belirtilen ondalık sayıyı eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) metodu


Belirtilen unicode karakteri eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) metodu


Dönüşüm desteklenmez. Her zaman InvalidCastException hatası fırlatır.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) metodu


Belirtilen null-dizgisini eşdeğer 8 bit tam sayı değerine dönüştürür.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```


### Dönen Değer

Sıfır.

## Convert::ToSByte(const char_t *) metodu


Belirtilen sayıyı temsil eden c-dizgisini eşdeğer 8 bit tam sayı değerine dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dizgi |

### Dönen Değer

Belirtilen c-dizgi tarafından temsil edilen sayıya eşit 8 bit tam sayı değeri

## Convert::ToSByte(const String\&) metodu


Belirtilen sayıyı temsil eden dizeyi eşdeğer 8 bit tam sayı değerine dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönen Değer

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit tam sayı değeri

## Convert::ToSByte(const String\&, int) metodu


Belirtilen sayıyı temsil eden dizeyi belirtilen tabanda eşdeğer 8 bit tam sayı değerine dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| from_base | int | Dizgenin temsil ettiği sayının tabanı |

### Dönen Değer

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit tam sayı değeri

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metodu


Belirtilen sayıyı temsil eden dizeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer işaretsiz 8 bit tam sayı değerine dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize formatı bilgisini içeren bir nesneye işaretçi |

### Dönen Değer

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit tam sayı değeri

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) metodu




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodu


Belirtilen sayıyı temsil eden dizeyi sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer 8 bit tam sayı değerine dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin izin verilen dize temsil stili belirtildiği bitwise birleştirmesi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize formatı bilgisini içeren bir nesneye işaretçi |

### Dönen Değer

Belirtilen dize tarafından temsil edilen sayıya eşit işaretsiz 8 bit tam sayı değeri

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metodu 




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) metodu 




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodu


Belirtilen kutulanmış değeri eşdeğer 8 bit tam sayı değerine dönüştürür.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Değeri dönüştürülecek nesneyi kutulayan paylaşımlı işaretçi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutulanmış değerin tipi [String](../../string/) ise kullanılacak dize formatı |

### Dönen Değer

Belirtilen kutulanmış değere eşdeğer 8 bit tam sayı değeri

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)