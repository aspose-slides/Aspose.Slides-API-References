---
title: GetString()
second_title: Aspose.Slides C++ API Referansı
description: Bayt tamponunu bir dizeye çözer.
type: docs
weight: 313
url: /tr/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) metodu

Bir bayt tamponunu dizeye çözer.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) okunacak baytlar. |
| byte_count | int | Giriş tamponu boyutu. |

### Dönüş Değeri

[String](../../../system/string/) çözülen karakterlerin.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) metodu

Bir bayt tamponunu dizeye çözer.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) okunacak baytlar. |

### Dönüş Değeri

[String](../../../system/string/) çözülen karakterlerin.

## Encoding::GetString(ArrayPtr\<uint8_t\>) metodu

Bir bayt tamponunu dizeye çözer.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) okunacak baytlar. |

### Dönüş Değeri

[String](../../../system/string/) çözülen karakterlerin.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) metodu

Bir bayt tamponunu dizeye çözer.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) okunacak baytlar. |

### Dönüş Değeri

[String](../../../system/string/) çözülen karakterlerin.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) metodu

Bir bayt tamponunu dizeye çözer.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) okunacak baytlar. |

### Dönüş Değeri

[String](../../../system/string/) çözülen karakterlerin.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) metodu

Bir bayt tamponunu dizeye çözer.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) okunacak baytlar. |
| index | int | Giriş tamponu ofseti. |
| count | int | Giriş tamponu boyutu. |

### Dönüş Değeri

[String](../../../system/string/) çözülen karakterlerin.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) metodu

Bir bayt tamponunu dizeye çözer.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) okunacak baytlar. |
| index | int | Giriş tamponu ofseti. |
| count | int | Giriş tamponu boyutu. |

### Dönüş Değeri

[String](../../../system/string/) çözülen karakterlerin.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) metodu

Bir bayt tamponunu dizeye çözer.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) okunacak baytlar. |
| index | int | Giriş tamponu ofseti. |
| count | int | Giriş tamponu boyutu. |

### Dönüş Değeri

[String](../../../system/string/) çözülen karakterlerin.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)