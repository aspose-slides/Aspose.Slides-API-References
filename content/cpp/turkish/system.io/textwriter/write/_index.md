---
title: Write()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen nesnenin dize temsili akışa yazılır.
type: docs
weight: 105
url: /tr/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) metodu


Belirtilen nesnenin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Yazılacak nesne |

## TextWriter::Write(bool) metodu


Belirtilen boolean değerinin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **bool** | Yazılacak değer |

## TextWriter::Write(char_t) metodu


Belirtilen karakter akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char_t | Yazılacak değer |

## TextWriter::Write(Decimal) metodu


Belirtilen [Decimal](../../../system/decimal/) nesnesinin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Yazılacak nesne |

## TextWriter::Write(double) metodu


Belirtilen çift duyarlıklı kayan nokta değerinin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **double** | Yazılacak değer |

## TextWriter::Write(int) metodu


Belirtilen 32-bit tam sayı değerinin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int | Yazılacak değer |

## TextWriter::Write(int64_t) metodu


Belirtilen 64-bit tam sayı değerinin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **int64_t** | Yazılacak değer |

## TextWriter::Write(float) metodu


Belirtilen tek duyarlıklı kayan nokta değerinin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **float** | Yazılacak değer |

## TextWriter::Write(const String\&) metodu


Belirtilen dize akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Yazılacak dize |

## TextWriter::Write(uint32_t) metodu


Belirtilen işaretsiz 32-bit tam sayı değerinin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **uint32_t** | Yazılacak değer |

## TextWriter::Write(uint64_t) metodu


Belirtilen işaretsiz 64-bit tam sayı değerinin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **uint64_t** | Yazılacak değer |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) metodu


Belirtilen diziden tüm karakterler akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Yazılacak karakterleri içeren dizi |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodu


Belirtilen karakter dizisinden belirli UTF-16 karakter alt aralığı akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Yazılacak karakterleri içeren dizi |
| index | **int32_t** | **buffer** içinde alt aralığın başladığı 0-tabanlı dizin |
| count | **int32_t** | Yazılacak karakter sayısı; **-1** değeri alt aralığın **buffer** dizisinin sonuna kadar devam edeceğini belirtir |

## TextWriter::Write(const char_t *) metodu


Belirtilen C-dizesi akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Yazılacak C-dizesi |

## TextWriter::Write(const TypeInfo\&) metodu


Belirtilen [TypeInfo](../../../system/typeinfo/) nesnesinin dize temsili akışa yazılır.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Yazılacak nesne |

## TextWriter::Write(const String\&, const TArgs\&...) metodu


Belirtilen değerler, belirtilen formata göre biçimlendirilerek akışa yazılır.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TArgs | Yazılacak değerlerin tip listesi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Dize biçimi |
| args | const TArgs\&... | Yazılacak değerler |

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [TextWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)