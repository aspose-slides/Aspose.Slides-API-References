---
title: EndsWith()
second_title: Aspose.Slides for C++ API Referansı
description: Dizenin belirtilen alt dizeyle bitip bitmediğini denetler.
type: docs
weight: 482
url: /tr/system/string/endswith/
---
## String::EndsWith(const String\&) const metod


Dizenin belirtilen alt dizeyle bitip bitmediğini denetler.

```cpp
bool System::String::EndsWith(const String &value) const
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../)\& | Arama dizesi. |

### Dönüş Değeri

Dizenin belirtilen alt dizeyle bittiği durumda true, aksi takdirde false.

## String::EndsWith(const String\&, System::StringComparison) const metod


Dizenin belirtilen alt dizeyle bitip bitmediğini denetler.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../)\& | Arama dizesi. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu, ayrıntılar için [System::StringComparison](../../stringcomparison/) bakın. |

### Dönüş Değeri

Dizenin belirtilen alt dizeyle bittiği durumda true, aksi takdirde false.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metod


Dizenin belirtilen alt dizeyle bitip bitmediğini denetler.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../)\& | Arama dizesi. |
| ignoreCase | **bool** | Karşılaştırmanın büyük/küçük harfe duyarlı olup olmadığını belirtir. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Dize karşılaştırması yapılırken kullanılacak kültür. |

### Dönüş Değeri

Dizenin belirtilen alt dizeyle bittiği durumda true, aksi takdirde false.

## İlgili

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)