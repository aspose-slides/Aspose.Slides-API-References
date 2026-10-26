---
title: Trim()
second_title: Aspose.Slides for C++ API Referansı
description: Dizgenin hem başındaki hem sonundaki tüm boşluk karakterlerini kaldırır.
type: docs
weight: 677
url: /tr/system/string/trim/
---
## String::Trim() const yöntemi

Dizgenin hem başındaki hem sonundaki tüm boşluk karakterlerini kaldırır.

```cpp
String System::String::Trim() const
```

### Dönüş Değeri

[String](../) başında veya sonunda boşluk olmadan.

## String::Trim(char_t) const yöntemi

Geçilen karakterin tüm örneklerini dizgenin hem başından hem sonundan kaldırır.

```cpp
String System::String::Trim(char_t ch) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ch | char_t | Kaldırılacak sembol. |

### Dönüş Değeri

Kaldırma sonucu.

## String::Trim(const String\&) const yöntemi

Geçilen karakterlerin tüm örneklerini dizgenin hem başından hem sonundan kaldırır.

```cpp
String System::String::Trim(const String &anyOf) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) kaldırılacak karakterler. |

### Dönüş Değeri

[String](../) kaldırılan karakterler olmadan.

## String::Trim(const ArrayPtr\<char_t\>\&) const yöntemi

Geçilen karakterlerin tüm örneklerini dizgenin hem başından hem sonundan kaldırır.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) kaldırılacak karakterler. |

### Dönüş Değeri

[String](../) kaldırılan karakterler olmadan.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [String](../)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)