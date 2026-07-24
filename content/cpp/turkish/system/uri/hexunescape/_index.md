---
title: HexUnescape()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bir karakterin onaltılık temsilini bir karaktere dönüştürür.
type: docs
weight: 443
url: /tr/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) metodu

Belirtilen bir karakterin onaltılık temsilini bir karaktere dönüştürür.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Bir karakterin onaltılık temsilini içeren bir dize |
| index | **int32_t**\& | **pattern** içinde bir karakterin onaltılık temsilinin başladığı konum |

### Dönüş Değeri

**index** konumundaki onaltılık kodlamayla temsil edilen karakter. **index** konumundaki karakter onaltılık olarak kodlanmamışsa, **index** konumundaki karakter döndürülür. **index** değeri, döndürülen karakteri izleyen karaktere işaret edecek şekilde artırılır.

## İlgili

* Sınıf [String](../../string/)
* Sınıf [Uri](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)