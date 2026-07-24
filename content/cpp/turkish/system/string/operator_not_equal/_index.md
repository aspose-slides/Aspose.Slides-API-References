---
title: operator!=()
second_title: Aspose.Slides for C++ API Referansı
description: Eşit olmayan karşılaştırma operatörü.
type: docs
weight: 313
url: /tr/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const metodu

Eşit olmayan karşılaştırma operatörü.

```cpp
bool System::String::operator!=(const String &str) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) mevcut olanı karşılaştırmak için. |

### Dönüş Değeri

false if both strings are null or both are not null and match, true otherwise.

## String::operator!=(std::nullptr_t) const metodu

Dizenin null olmadığını kontrol eder. [IsNull()](../isnull/) çağrısı ile aynı mantığı uygular.

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### Dönüş Değeri

false if string is null, true otherwise.

## İlgili

* Sınıf [String](../)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)