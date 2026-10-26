---
title: Parse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen isimdeki belirtilen enum sabitinin değerini kutular. Bir parametre, enum sabitinin adını belirten dizeyi yorumlarken büyük/küçük harfin göz ardı edilip edilmeyeceğini belirtir.
type: docs
weight: 53
url: /tr/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) method

Belirtilen isimdeki belirtilen enum sabitinin değerini kutular. Bir parametre, enum sabitinin adını belirten dizeyi yorumlarken büyük/küçük harf duyarlılığının göz ardı edilip edilmeyeceğini belirtir.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Enum tipini belirtir |
| str | const [String](../../string/)\& | Kutulanacak değerin bulunduğu enum sabitinin adı |
| ignoreCase | **bool** | Enum sabitinin adını temsil eden dizeyi yorumlarken büyük/küçük harfin göz ardı edilip edilmeyeceğini belirtir |

### Dönüş Değeri

Belirtilen enum sabitinin kutulanmış değerini temsil eden nesneye ait bir paylaşımlı işaretçi

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) method

Belirtilen isimdeki belirtilen enum sabitinin değerini kutular.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Enum tipini belirtir |
| str | const [String](../../string/)\& | Kutulanacak değerin bulunduğu enum sabitinin adı |

### Dönüş Değeri

Belirtilen enum sabitinin kutulanmış değerini temsil eden nesneye ait bir paylaşımlı işaretçi

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Object](../../object/)
* Sınıf [TypeInfo](../../typeinfo/)
* Sınıf [String](../../string/)
* Sınıf [BoxedValueBase](../)
* İsim Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)