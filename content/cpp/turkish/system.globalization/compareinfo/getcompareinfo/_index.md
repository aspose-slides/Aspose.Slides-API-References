---
title: GetCompareInfo()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen kültürle ilişkili CompareInfo nesnesini alır ve belirtilen assembly içinde dize karşılaştırma yöntemlerini kullanır.
type: docs
weight: 183
url: /tr/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) metodu


Belirtilen kültürle ilişkili [CompareInfo](../) elde eder ve belirtilen derleme içinde dize karşılaştırma yöntemlerini kullanır.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### Dönüş Değeri

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) metodu


Belirtilen kültürle ilişkili [CompareInfo](../) elde eder ve belirtilen derleme içinde dize karşılaştırma yöntemlerini kullanır.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### Dönüş Değeri

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(int) metodu


Belirtilen kültürle ilişkili [CompareInfo](../) elde eder.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |

### Dönüş Değeri

[CompareInfo](../) object.

## CompareInfo::GetCompareInfo(const String\&) metodu


Belirtilen kültürle ilişkili [CompareInfo](../) elde eder.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |

### Dönüş Değeri

[CompareInfo](../) object.

## Ayrıca Bakınız

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Assembly](../../../system.reflection/assembly/)
* Sınıf [CompareInfo](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Globalization](../../)
* Kütüphane [Aspose.Slides](../../../)