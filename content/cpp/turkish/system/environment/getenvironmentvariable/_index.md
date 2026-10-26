---
title: GetEnvironmentVariable()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ortam değişkeninin değerini mevcut süreçle ilişkili olarak döndürür.
type: docs
weight: 287
url: /tr/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) method

Belirtilen ortam değişkeninin değerini mevcut süreçle ilişkili olarak döndürür.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Alınacak değişkenin adını içeren dize |

### Dönüş Değeri

Belirtilen değişkenin değeri

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) method

Belirtilen ortam değişkeninin değerini belirtilen konumdan döndürür.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Alınacak değişkenin adını içeren dize |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Değişkenin konumu |

### Dönüş Değeri

Belirtilen değişkenin değeri

## Ayrıca Bakınız

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Sınıf [String](../../string/)
* Yapı [Environment](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)