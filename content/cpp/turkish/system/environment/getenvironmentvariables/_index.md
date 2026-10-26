--- 
title: GetEnvironmentVariables()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli işlemle ilişkili tüm ortam değişkeni adlarını ve değerlerini içeren bir sözlük döndürür.
type: docs
weight: 326
url: /tr/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() metodu

Geçerli işlemle ilişkili tüm ortam değişkeni adları ve değerlerini içeren bir sözlük döndürür.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) metodu

Belirtilen konumdaki tüm ortam değişkenlerinin adlarını ve değerlerini içeren bir sözlük döndürür.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Değişkenlerin konumu |

### Dönüş Değeri

Belirtilen konumdaki tüm ortam değişkenlerinin adlarını ve değerlerini içeren bir sözlük

## İlgili

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Sınıf [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Sınıf [String](../../string/)
* Struct [Environment](../)
* Ad alanı [System](../../)
* Library [Aspose.Slides](../../../)