---
title: NewLineHandling
second_title: Aspose.Slides için C++ API Referansı
description: Satır sonu karakterlerinin nasıl işleneceğini belirtir.
type: docs
weight: 690
url: /tr/system.xml/newlinehandling/
---
## NewLineHandling enum


Satır sonu karakterlerinin nasıl işleneceğini belirtir.

```cpp
enum class NewLineHandling
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Replace | 0 | Yeni satır karakterleri, [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/) değerinde belirtilen karakterle eşleşecek şekilde değiştirilir. |
| Entitize | 1 | Yeni satır karakterleri entity'ye dönüştürülür. Bu ayar, çıktı normalleştirici bir [XmlReader](../xmlreader/) tarafından okunduğunda tüm karakterleri korur. |
| None | 2 | Yeni satır karakterleri değişmeden kalır. Çıktı, girdiye aynıdır. |

## İlgili

* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)