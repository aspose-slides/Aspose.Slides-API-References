---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizeyi eşdeğer enum sabiti olarak dönüştürmeye çalışır.
type: docs
weight: 79
url: /tr/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) metot

Belirtilen dizeyi eşdeğer enum sabiti olarak dönüştürmeye çalışır.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) yorumlanan ve enum sabitinin adını içeren |
| result | E\& | Dönüşüm başarılı olduğunda dönüşüm sonucunu içeren çıktı parametresi |

### Dönüş Değeri

Dönüşüm başarılıysa true, aksi takdirde false

## Enum::TryParse(const String\&, bool, E\&) metot

Belirtilen dizeyi eşdeğer enum sabiti olarak dönüştürmeye çalışır.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) yorumlanan ve enum sabitinin adını içeren |
| ignoreCase | **bool** | Dize yorumlanırken büyük/küçük harf duyarlılığının göz ardı edilip edilmeyeceğini belirtir |
| result | E\& | Dönüşüm başarılı olduğunda dönüşüm sonucunu içeren çıktı parametresi |

### Dönüş Değeri

Dönüşüm başarılıysa true, aksi takdirde false

## Ayrıca Bakınız

* Sınıf [String](../../string/)
* Yapı [Enum](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)