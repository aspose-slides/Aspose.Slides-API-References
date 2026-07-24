---
title: TrimStart()
second_title: Aspose.Slides C++ API Referansı
description: Dizgenin başındaki tüm boşluk karakterlerini kaldırır.
type: docs
weight: 690
url: /tr/system/string/trimstart/
---
## String::TrimStart() const metod

Dizgenin başlangıcındaki tüm boşluk karakterlerini kaldırır.

```cpp
String System::String::TrimStart() const
```


### Dönüş Değeri

[String](../) başında boşluk yok.

## String::TrimStart(char_t) const metod

Geçilen karakterin dizgenin başlangıcından tüm görünümlerini kaldırır.

```cpp
String System::String::TrimStart(char_t ch) const
```


### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| ch | char_t | Kaldırılacak sembol. |

### Dönüş Değeri

Kaldırma sonucu.

## String::TrimStart(const String\&) const metod

Geçilen karakterlerin dizgenin başlangıcından tüm görünümlerini kaldırır.

```cpp
String System::String::TrimStart(const String &anyOf) const
```


### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) kaldırılacak karakterlerin. |

### Dönüş Değeri

[String](../) kaldırılmış karakterler olmadan.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const metod

Geçilen karakterlerin dizgenin başlangıcından tüm görünümlerini kaldırır.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```


### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) kaldırılacak karakterlerin. |

### Dönüş Değeri

[String](../) kaldırılmış karakterler olmadan.

## İlgili

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [String](../)
* İsim Alanı [System](../../)
* Library [Aspose.Slides](../../../)