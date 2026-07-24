---
title: ToBoolean()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen boolean değeri döndürür.
type: docs
weight: 79
url: /tr/system/convert/toboolean/
---
## Convert::ToBoolean(bool) metodu


Belirtilen boolean değeri döndürür.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) metodu


Belirtilen 8-bitlik işaretsiz tam sayıyı eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) metodu


Belirtilen 8-bitlik işaretli tam sayıyı eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) metodu


Belirtilen 16-bitlik işaretsiz tam sayıyı eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) metodu


Belirtilen 16-bitlik işaretli tam sayıyı eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) metodu


Belirtilen 32-bitlik işaretsiz tam sayıyı eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) metodu


Belirtilen 32-bitlik işaretli tam sayıyı eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) metodu


Belirtilen 64-bitlik işaretsiz tam sayıyı eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) metodu


Belirtilen 64-bitlik işaretli tam sayıyı eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) metodu


Belirtilen kayan nokta sayısını eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) metodu


Belirtilen çift hassasiyetli kayan nokta sayısını eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) metodu


Belirtilen ondalık sayıyı eşdeğer bir boolean değere dönüştürür.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) metodu


Dönüştürme desteklenmez. Her zaman InvalidCastException hatası fırlatır.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) metodu


Dönüştürme desteklenmez. Her zaman InvalidCastException hatası fırlatır.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) metodu


Belirtilen null-dizgesini eşdeğer bir boolean değere dönüştürür.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Dönüş Değeri

False.

## Convert::ToBoolean(const char_t *) metodu


Belirtilen c-dizgesini bool tipinde bir değere dönüştürür.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Dönüştürülecek c-dizgesi |

### Dönüş Değeri

Belirtilen c-dizgesi "True" ise doğru, belirtilen c-dizgesi "False" ise yanlış döner.

## Convert::ToBoolean(const String\&) metodu


Belirtilen dizeyi bool tipinde bir değere dönüştürür.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönüş Değeri

Belirtilen c-dizgesi "True" ise doğru, belirtilen dize "False" ise yanlış döner.

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) metodu


Belirtilen dizeyi bool tipinde bir değere dönüştürür.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |

### Dönüş Değeri

Belirtilen c-dizgesi "True" ise doğru, belirtilen dize "False" ise yanlış döner.

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodu


Belirtilen kutu-değerini eşdeğer bir boolean değere dönüştürür.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Dönüştürülecek değeri paketleyen nesneye ait paylaşımlı işaretçi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Paketlenmiş değerin tipi [String](../../string/) ise kullanılacak dize biçimi |

### Dönüş Değeri

Belirtilen paketlenmiş değere eşdeğer bir boolean değer.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)