---
title: Parse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen enum tipinde belirtilen isimdeki enum sabitinin değerini temsil eden bir nesne döndürür.
type: docs
weight: 27
url: /tr/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) yöntemi

Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) nesnesi, döndürülecek enum değerinin tipini temsil eder |
| str | const [String](../../string/)\& | Enum sabitinin adı |
| ignoreCase | **bool** | Enum sabitinin adını yorumlarken büyük/küçük harf duyarlılığının göz ardı edilip edilmeyeceğini belirtir |

### Dönüş Değeri

**str** içinde belirtilen enum sabitinin değerini temsil eden bir nesne.

## Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Object](../../object/)
* Sınıf [TypeInfo](../../typeinfo/)
* Sınıf [String](../../string/)
* Sınıf [EnumValuesBase](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)