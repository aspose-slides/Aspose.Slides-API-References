---
title: Insert()
second_title: Aspose.Slides for C++ API Referansı
description: Dizgiyi builder'ın sabit konumuna ekler.
type: docs
weight: 183
url: /tr/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) yöntemi

Dizgiyi builder'ın sabit konumuna ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Karakterlerin ekleneceği konum. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) eklemek için. |

### Dönüş Değeri

Bu işaretçi.

## StringBuilder::Insert(int32_t, const String\&, int32_t) yöntemi

Yinelemeli dizgiyi builder'ın sabit konumuna ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Karakterlerin ekleneceği konum. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) eklemek için. |
| count | **int32_t** | **value** dizgisini kaç kez tekrarlayacağını belirtir. |

### Dönüş Değeri

Bu işaretçi.

## StringBuilder::Insert(int, char_t) yöntemi

Karakteri builder'ın sabit konumuna ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Karakterlerin ekleneceği konum. |
| ch | char_t | Eklenecek karakter. |

### Dönüş Değeri

Bu işaretçi.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) yöntemi

Karakterleri builder'ın sabit konumuna ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Karakterlerin ekleneceği konum. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) eklemek için dilim. |
| startIndex | int | [Array](../../../system/array/) dilim başlangıç indeksi. |
| charCount | int | [Array](../../../system/array/) dilim uzunluğu. |

### Dönüş Değeri

Bu işaretçi.

## StringBuilder::Insert(int, T) yöntemi

Değeri builder'ın sabit konumuna ekler.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Parametre | tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Karakterlerin ekleneceği konum. |
| value | T | Formatlanıp eklenecek değer. |

### Dönüş Değeri

Bu işaretçi.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [StringBuilder](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)