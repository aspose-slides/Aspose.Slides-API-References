---
title: Append()
second_title: Aspose.Slides for C++ API Referansı
description: Yapıcıya karakter ekler.
type: docs
weight: 118
url: /tr/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) metodu

Yapıcıya karakter ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Karakter değeri. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(char_t, int) metodu

Yapıcıya karakterler ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Karakter değeri. |
| count | int | Eklenecek karakterin kaç kez tekrarlanacağını belirtir. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(const ArrayPtr\<char_t\>\>) metodu

Yapıcıya karakter dizisi ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Eklenecek karakterler. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) metodu

Yapıcıya karakter dizisi dilimini ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Eklenecek karakterler. |
| startIndex | int | Dilim başlangıç indeksi. |
| charCount | int | Dilim uzunluğu. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(const String\&) metodu

Yapıcıya dize ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) eklemek için. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(const String\&, int, int) metodu

Yapıcıya dize dilimi ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) eklemek için. |
| startIndex | int | Dilim başlangıç indeksi. |
| charCount | int | Dilim uzunluğu. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(const SharedPtr\<T\>\&) metodu

Yapıcıya nesnenin dize temsilini ekler.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../../system/object/) türü. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) serileştirip eklemek için. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) metodu

Yapıcının içeriğini yapıcıya ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | İçeriği eklenecek yapıcı. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(float) metodu

Yapıcıya kayan nokta değeri ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| f | **float** | Serileştirip eklemek için değer. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(double) metodu

Yapıcıya kayan nokta değeri ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| df | **double** | Serileştirip eklemek için değer. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(int) metodu

Yapıcıya tam sayı değeri ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | int | Serileştirip eklemek için değer. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(T) metodu

Yapıcıya aritmetik değer ekler.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aritmetik tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T | Serileştirip eklemek için değer. |

### Dönüş Değeri

Bu gösterici.

## StringBuilder::Append(E) metodu

Yapıcıya enum değerinin dize temsilini ekler.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| E | [Enum](../../../system/enum/) tür. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| e | E | Serileştirip eklemek için değer. |

### Dönüş Değeri

Bu gösterici.

## Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [StringBuilder](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)