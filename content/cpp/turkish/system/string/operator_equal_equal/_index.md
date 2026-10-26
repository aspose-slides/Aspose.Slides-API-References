---
title: operator==()
second_title: Aspose.Slides for C++ API Referansı
description: Eşitlik karşılaştırma operatörü.
type: docs
weight: 300
url: /tr/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const method

Eşitlik karşılaştırma operatörü.

```cpp
bool System::String::operator==(const String &str) const
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) geçerli olanla karşılaştırmak için. |

### Dönüş Değeri

her iki dize de null ise veya ikisi de null değil ve eşleşiyorsa true, aksi takdirde false.

## String::operator==(std::nullptr_t) const method

Dizenin null olup olmadığını kontrol eder. [IsNull()](../isnull/) çağrısı ile aynı mantığı uygular.

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### Dönüş Değeri

dize null ise true, aksi takdirde false.

## İlgili

* Sınıf [String](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)