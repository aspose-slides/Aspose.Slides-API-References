---
title: ValidationType
second_title: Aspose.Slides for C++ API Referansı
description: Gerçekleştirilecek doğrulama türünü belirtir.
type: docs
weight: 729
url: /tr/system.xml/validationtype/
---
## ValidationType enum

Doğrulamanın yapılacağı türü belirler.

```cpp
enum class ValidationType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Hiçbir doğrulama yapılmaz ve doğrulama hataları atılmaz. Bu ayar, XML 1.0 uyumlu doğrulama yapmayan bir ayrıştırıcı oluşturur. |
| Auto | 1 | DTD veya şema bilgisi bulunursa doğrulama yapılır. |
| DTD | 2 | DTD'ye göre doğrulama yapılır. |
| XDR | 3 | Satır içi XDR şemaları dahil olmak üzere XML-Data Reduced (XDR) şemalarına göre doğrulama yapılır. XDR şemaları, **x-schema** ad alanı öneki veya [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) değeri kullanılarak tanınır. |
| Schema | 4 | Satır içi XML Şemaları dahil olmak üzere XML [Schema](../../system.xml.schema/) tanım dili (XSD) şemalarına göre doğrulama yapılır. XML Şemaları, **schemaLocation** özniteliği kullanılarak veya sağlanan **Schemas** aracılığıyla ad alanı URI'leriyle ilişkilendirilir. |

## Ayrıca Bakınız

* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)