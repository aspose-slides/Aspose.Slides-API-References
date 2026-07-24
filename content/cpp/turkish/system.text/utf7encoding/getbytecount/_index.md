---
title: GetByteCount()
second_title: Aspose.Slides for C++ API Referansı
description: Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.
type: docs
weight: 157
url: /tr/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) metot


Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Karakter tamponu. |
| count | int | [Buffer](../../../system/buffer/) boyut. |

### Return Value

Gerekli tampon boyutu.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metot


Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter tamponu. |
| index | int | Dilim başlangıcı. |
| count | int | Dilim boyutu. |

### Return Value

Gerekli tampon boyutu.

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metot


Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Karakter tamponu. |
| index | int | Dilim başlangıcı. |
| count | int | Dilim boyutu. |

### Return Value

Gerekli tampon boyutu.

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metot


Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Karakter tamponu. |
| index | int | Dilim başlangıcı. |
| count | int | Dilim boyutu. |

### Return Value

Gerekli tampon boyutu.

## UTF7Encoding::GetByteCount(const String\&) metot


Bir dizeyi kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) kodlamak için. |

### Return Value

Gerekli tampon boyutu.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) metot


Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter tamponu. |

### Return Value

Gerekli tampon boyutu.

## UTF7Encoding::GetByteCount(const char_t *, int) metot


Bir karakter tamponunu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Karakter tamponu. |
| count | int | [Buffer](../../../system/buffer/) boyut. |

### Return Value

Gerekli tampon boyutu.

## See Also

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [UTF7Encoding](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)