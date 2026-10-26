---
title: operator>>()
second_title: Aspose.Slides için C++ API Referansı
description: Giriş akışından UTF-8 kodlamasını kullanarak bir dize alır.
type: docs
weight: 3004
url: /tr/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) fonksiyon

Giriş akışından UTF-8 kodlamasını kullanarak bir dize alır.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| in | std::istream\& | Bir giriş akışı nesnesi (**basic_ostream**'un **char** ile örneklenmesi). |
| str | [String](../string/)\& | Giriş akışından okunacak bir dize. |

### Dönüş Değeri

Dizenin çıkarıldığı bir giriş akışı.

## System::operator>>(std::wistream\&, String\&) fonksiyon

Giriş akışından bir dize alır.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| in | std::wistream\& | Bir giriş akışı nesnesi (**basic_ostream**'un ****wchar_t**** ile örneklenmesi). |
| str | [String](../string/)\& | Giriş akışından okunacak bir dize. |

### Dönüş Değeri

Dizenin çıkarıldığı bir giriş akışı.

## Ayrıca

* Sınıf [String](../string/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)