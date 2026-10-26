---
title: GetCultureInfo()
second_title: Aspose.Slides for C++ API Referansı
description: İsmiyle kültürü alır. CreateSpecificCulture ile aynıdır.
type: docs
weight: 586
url: /tr/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) metodu


İsimle kültürü alır. CreateSpecificCulture ile aynıdır.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Önceden tanımlı kültür adı veya mevcut kültür nesnesinin adı. |

### Dönüş Değeri

Yeni oluşturulan kültür nesnesi.

## CultureInfo::GetCultureInfo(const String\&, const String\&) metodu


İsimle kültürü alır.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kültür adı. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | [TextInfo](../../textinfo/) ve [CompareInfo](../../compareinfo/) nesneleri için kullanılan kültür adı. |

### Dönüş Değeri

Kültür nesnesi.

## CultureInfo::GetCultureInfo(int32_t) metodu


Kimlikle kültürü alır.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| culture | **int32_t** | Kültür tanımlayıcısı. |

### Dönüş Değeri

Yeni oluşturulan kültür nesnesi.

## İlgili

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [CultureInfo](../)
* Ad alanı [System::Globalization](../../)
* Kütüphane [Aspose.Slides](../../../)