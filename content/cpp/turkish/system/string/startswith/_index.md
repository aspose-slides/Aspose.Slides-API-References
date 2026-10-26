---
title: StartsWith()
second_title: Aspose.Slides için C++ API Referansı
description: Dizgenin belirtilen alt dize ile başlayıp başlamadığını kontrol eder.
type: docs
weight: 469
url: /tr/system/string/startswith/
---
## String::StartsWith(const String\&) const metot


Dizgenin belirtilen alt dize ile başlayıp başlamadığını kontrol eder.

```cpp
bool System::String::StartsWith(const String &value) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../)\& | Arama dizesi. |

### Dönüş Değeri

true ise dize belirtilen alt dize ile başlar, false ise aksi takdirde.

## String::StartsWith(const String\&, System::StringComparison) const metot


Dizgenin belirtilen alt dize ile başlayıp başlamadığını kontrol eder.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../)\& | Arama dizesi. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu, detaylar için [System::StringComparison](../../stringcomparison/) bakınız. |

### Dönüş Değeri

true ise dize belirtilen alt dize ile başlar, false ise aksi takdirde.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metot


Dizgenin belirtilen alt dize ile başlayıp başlamadığını kontrol eder.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../)\& | Arama dizesi. |
| ignoreCase | **bool** | Karşılaştırmanın büyük/küçük harfe duyarsız olup olmadığını belirler. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Dize karşılaştırması yapılırken kullanılacak kültür. |

### Dönüş Değeri

true ise dize belirtilen alt dize ile başlar, false ise aksi takdirde.

## İlgili

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* İsim alanı [System](../../)
* Library [Aspose.Slides](../../../)