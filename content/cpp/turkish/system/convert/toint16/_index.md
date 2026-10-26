---
title: ToInt16()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen boolean değeri eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.
type: docs
weight: 131
url: /tr/system/convert/toint16/
---
## Convert::ToInt16(bool) metodu


Belirtilen boolean değerini eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) metodu


Belirtilen 8-bit işaretsiz tamsayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) metodu


Belirtilen 8-bit işaretli tamsayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) metodu


Belirtilen 16-bit işaretsiz tamsayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) metodu


Belirtilen 16-bit işaretli tamsayıyı döndürür.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) metodu


Belirtilen 32-bit işaretsiz tamsayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) metodu


Belirtilen 32-bit işaretli tamsayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) metodu


Belirtilen 64-bit işaretsiz tamsayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) metodu


Belirtilen 64-bit işaretli tamsayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) metodu


Belirtilen float sayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) metodu


Belirtilen double sayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal&) metodu


Belirtilen decimal sayıyı eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) metodu


Belirtilen unicode karakteri eşdeğer bir 16-bit işaretli tamsayıya dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) metodu


Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) metodu


Belirtilen null dizesini eşdeğer 16-bit tamsayı değerine dönüştürür.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```


### Dönüş Değeri

Sıfır.

## Convert::ToInt16(const char_t *) metodu


Bir sayının dize temsili içeren belirtilen c-dizesini eşdeğer 16-bit tamsayı değerine dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dize |

### Dönüş Değeri

Belirtilen c-dizesiyle temsil edilen sayıya eşit 16-bit tamsayı değeri

## Convert::ToInt16(const String&) metodu


Bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 16-bit tamsayı değerine dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönüş Değeri

Belirtilen dizeyle temsil edilen sayıya eşit 16-bit tamsayı değeri

## Convert::ToInt16(const String&, int) metodu


Belirtilen temelde bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 16-bit tamsayı değerine dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| from_base | int | Dizeyle temsil edilen sayının tabanı |

### Dönüş Değeri

Belirtilen dizeyle temsil edilen sayıya eşit 16-bit tamsayı değeri

## Convert::ToInt16(const String&, const SharedPtr<IFormatProvider>&) metodu


Sağlanan biçimlendirme bilgilerini kullanarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 16-bit tamsayı değerine dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize format bilgilerini içeren nesneye işaretçi |

### Dönüş Değeri

Belirtilen dizeyle temsil edilen sayıya eşit 16-bit tamsayı değeri

## Convert::ToInt16(const String&, const SharedPtr<Globalization::CultureInfo>&) metodu




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String&, const SharedPtr<Globalization::NumberFormatInfo>&) metodu




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String&, std::nullptr_t) metodu




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&) metodu


Sağlanan biçimlendirme bilgileri ve sayı stili kullanarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 16-bit tamsayı değerine dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde birleşimi; sayının dize temsili için izin verilen stili belirtir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize format bilgilerini içeren nesneye işaretçi |

### Dönüş Değeri

Belirtilen dizeyle temsil edilen sayıya eşit 16-bit tamsayı değeri

## Convert::ToInt16(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&) metodu




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&) metodu




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String&, Globalization::NumberStyles, std::nullptr_t) metodu




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) metodu




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr<Object>&, const SharedPtr<IFormatProvider>&) metodu


Belirtilen kutulanmış değeri eşdeğer 16-bit tamsayı değerine dönüştürür.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Değeri dönüştürmek için kutulayan nesneye işaret eden paylaşımlı gösterici |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutulanmış değerin türü [String](../../string/) olduğunda kullanılacak dize biçimi |

### Dönüş Değeri

Belirtilen kutulanmış değere eşdeğer bir 16-bit tamsayı değeri

## Bkz

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Decimal](../../decimal/)
* Sınıf [DateTime](../../datetime/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Sınıf [Object](../../object/)
* Yapı [Convert](../)
* Yapı [Enum](../../enum/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)