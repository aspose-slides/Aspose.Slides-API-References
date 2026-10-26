---
title: IsSuffix()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen karşılaştırma seçenekleri kullanılarak, belirtilen dizenin belirtilen son ek ile bitip bitmediğini denetler.
type: docs
weight: 118
url: /tr/system.globalization/compareinfo/issuffix/
---
## CompareInfo::IsSuffix(const String\&, const String\&, CompareOptions) const metot

Belirtilen karşılaştırma seçenekleri kullanılarak, belirtilen dizenin belirtilen son ek ile bitip bitmediğini denetler.

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix, CompareOptions options) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | Kaynak dize. |
| suffix | const [String](../../../system/string/)\& | Son ek dizesi. |
| options | [CompareOptions](../../compareoptions/) | Karşılaştırma seçenekleri. |

### Dönüş Değeri

True if string ends with suffix; otherwise false.

## CompareInfo::IsSuffix(const String\&, const String\&) const metot

Belirtilen dizenin belirtilen son ek ile bitip bitmediğini denetler.

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | Kaynak dize. |
| suffix | const [String](../../../system/string/)\& | Son ek dizesi. |

### Dönüş Değeri

True if string ends with suffix; otherwise false.

## Ayrıca Bakınız

* Enum [CompareOptions](../../compareoptions/)
* Sınıf [String](../../../system/string/)
* Sınıf [CompareInfo](../)
* İsim Uzayı [System::Globalization](../../)
* Library [Aspose.Slides](../../../)