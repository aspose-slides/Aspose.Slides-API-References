---
title: ToChar()
second_title: Aspose.Slides için C++ API Referansı
description: Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır.
type: docs
weight: 118
url: /tr/system/convert/tochar/
---
## Convert::ToChar(bool) method

Dönüştürme desteklenmiyor. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) method

Belirtilen 8 bit işaretsiz tamsayıyı eşdeğer bir Unicode karakterine dönüştürür.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) method

Belirtilen 8 bit işaretli tamsayıyı eşdeğer bir Unicode karakterine dönüştürür.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) method

Belirtilen 16 bit işaretsiz tamsayıyı eşdeğer bir Unicode karakterine dönüştürür.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) method

Belirtilen 16 bit işaretli tamsayıyı eşdeğer bir Unicode karakterine dönüştürür.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) method

Belirtilen 32 bit işaretsiz tamsayıyı eşdeğer bir Unicode karakterine dönüştürür.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) method

Belirtilen 32 bit işaretli tamsayıyı eşdeğer bir Unicode karakterine dönüştürür.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) method

Belirtilen 64 bit işaretsiz tamsayıyı eşdeğer bir Unicode karakterine dönüştürür.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) method

Belirtilen 64 bit işaretli tamsayıyı eşdeğer bir Unicode karakterine dönüştürür.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) method

Dönüştürme desteklenmiyor. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) method

Dönüştürme desteklenmiyor. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) method

Dönüştürme desteklenmiyor. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) method

Belirtilen Unicode karakterini döndürür.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) method

Dönüştürme desteklenmiyor. Her zaman InvalidCastException istisnası fırlatır.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) method

Belirtilen c-dizgesinin ilk ve tek karakterini bir char_t değerine dönüştürür.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dizgesi; c-dizgesinin tam olarak 1 karakter uzunluğunda olması beklenir. |

### Dönüş Değeri

Belirtilen c-dizgesinin ilk ve tek karakteri, eğer tam olarak 1 karakter uzunluğunda ise; aksi takdirde - 0

## Convert::ToChar(const String\&) method

Belirtilen stringin ilk ve tek karakterini bir char_t değerine dönüştürür.

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek string; stringin tam olarak 1 karakter uzunluğunda olması beklenir. |

### Dönüş Değeri

Belirtilen stringin ilk ve tek karakteri, eğer tam olarak 1 karakter uzunluğunda ise; aksi takdirde - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Belirtilen stringin ilk ve tek karakterini bir char_t değerine dönüştürür.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek string; stringin tam olarak 1 karakter uzunluğunda olması beklenir. |

### Dönüş Değeri

Belirtilen stringin ilk ve tek karakteri, eğer tam olarak 1 karakter uzunluğunda ise, aksi takdirde - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

Belirtilen kutulmuş değeri eşdeğer bir Unicode karakterine dönüştürür.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Dönüştürülecek değeri kutulayan nesnenin paylaşımlı işaretçisi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kutulanan değerin tipi [String](../../string/) ise kullanılacak dize biçimi |

### Dönüş Değeri

Belirtilen kutulanmış değere eşdeğer bir Unicode karakteri

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Decimal](../../decimal/)
* Sınıf [DateTime](../../datetime/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [Object](../../object/)
* Yapı [Convert](../)
* İsim Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)