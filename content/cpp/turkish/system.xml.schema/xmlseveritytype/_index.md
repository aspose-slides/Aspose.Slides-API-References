---
title: XmlSeverityType
second_title: Aspose.Slides for C++ API Referansı
description: Doğrulama olayının şiddetini temsil eder.
type: docs
weight: 1080
url: /tr/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

Doğrulama olayının şiddetini temsil eder.

```cpp
enum class XmlSeverityType
```

### Değerler

| Name | Value | Description |
| --- | --- | --- |
| Error | 0 | Geçerli bir belge doğrulanırken bir doğrulama hatasının oluştuğunu gösterir. Bu, belge türü tanımları (DTDs) ve XML [Schema](../) tanımlama dili (XSD) şemaları için geçerlidir. Dünya Çapında [Web](../../system.web/) Konsorsiyumu (W3C) geçerlilik kısıtlamaları hata olarak kabul edilir. Eğer bir doğrulama olayı işleyicisi oluşturulmamışsa, hatalar bir istisna fırlatır. |
| Warning | 1 | Bir doğrulama olayının meydana geldiğini ancak bunun bir hata olmadığını gösterir. Uyarı genellikle bir DTD olmadığında veya belirli bir öğe ya da özniteliği doğrulamak için XML [Schema](../) bulunmadığında verilir. Hataların aksine, uyarılar doğrulama olayı işleyicisi yoksa bir istisna fırlatmaz. |

## Ayrıca Bakınız

* Ad alanı [System::Xml::Schema](../)
* Kitaplık [Aspose.Slides](../../)