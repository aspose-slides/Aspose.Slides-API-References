---
title: ToDecimal()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen boolean değerini eşdeğer bir decimal sayıya dönüştürür.
type: docs
weight: 235
url: /tr/system/convert/todecimal/
---
## Convert::ToDecimal(bool) metod

Belirtilen boolean değerini eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) metod

Belirtilen 8-bit işaretsiz tamsayıyı eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) metod

Belirtilen 8-bit işaretli tamsayıyı eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) metod

Belirtilen 16-bit işaretsiz tamsayıyı eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) metod

Belirtilen 16-bit işaretli tamsayıyı eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) metod

Belirtilen 32-bit işaretsiz tamsayıyı eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) metod

Belirtilen 32-bit işaretli tamsayıyı eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) metod

Belirtilen 64-bit işaretsiz tamsayıyı eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) metod

Belirtilen 64-bit işaretli tamsayıyı eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) metod

Belirtilen float sayısını eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) metod

Belirtilen double sayısını eşdeğer bir decimal sayıya dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) metod

Belirtilen decimal sayıyı döndürür.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) metod

Dönüştürme desteklenmez. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) metod

Dönüştürme desteklenmez. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) metod

Belirtilen null-stringi eşdeğer [Decimal](../../decimal/) değerine dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### Dönüş Değeri

Zero.

## Convert::ToDecimal(const char_t *) metod

Belirtilen c-string içinde sayı temsilinin bulunduğu c-dizgiyi eşdeğer [Decimal](../../decimal/) değerine dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-string |

### Dönüş Değeri

Belirtilen c-string tarafından temsil edilen sayıya eşit [Decimal](../../decimal/) değeri

## Convert::ToDecimal(const String\&) metod

Belirtilen string içinde sayı temsilinin bulunduğu stringi eşdeğer [Decimal](../../decimal/) değerine dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek string |

### Dönüş Değeri

Belirtilen string tarafından temsil edilen sayıya eşit [Decimal](../../decimal/) değeri

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Sağlanan formatlama bilgilerini kullanarak belirtilen string içinde sayı temsilinin bulunduğu stringi eşdeğer [Decimal](../../decimal/) değerine dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek string |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | String biçim bilgilerini içeren nesnenin işaretçisi |

### Dönüş Değeri

Belirtilen string tarafından temsil edilen sayıya eşit [Decimal](../../decimal/) değeri

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Belirtilen sayı stillerini ve formatlama bilgilerini kullanarak belirtilen string içinde sayı temsilinin bulunduğu stringi eşdeğer [Decimal](../../decimal/) değerine dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek string |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin izin verilen temsil stilini belirten bit düzeyinde birleşim |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | String biçim bilgilerini içeren nesnenin işaretçisi |

### Dönüş Değeri

Belirtilen string tarafından temsil edilen sayıya eşit [Decimal](../../decimal/) değeri

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod

Belirtilen kutulanmış değeri eşdeğer [Decimal](../../decimal/) değerine dönüştürür.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Dönüştürülecek değeri kutulayan nesneye ortak işaretçi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutulanmış değerin tipi [String](../../string/) olduğunda kullanılacak string biçim bilgisi |

### Dönüş Değeri

Belirtilen kutulanmış değere eşdeğer bir [Decimal](../../decimal/) değeri

## İlgili

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)