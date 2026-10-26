---
title: ConformanceLevel
second_title: Aspose.Slides for C++ API Referansı
description: XmlReader ve XmlWriter nesnelerinin gerçekleştirdiği giriş ve çıkış denetiminin miktarını belirtir.
type: docs
weight: 625
url: /tr/system.xml/conformancelevel/
---
## ConformanceLevel enum

Specifies the amount of input or output checking that [XmlReader](../xmlreader/) and [XmlWriter](../xmlwriter/) objects perform.

```cpp
enum class ConformanceLevel
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | 0 | [XmlReader](../xmlreader/) veya [XmlWriter](../xmlwriter/) nesnesi, belge seviyesi mi yoksa parça seviyesi mi denetiminin yapılması gerektiğini otomatik olarak algılar ve uygun denetimi gerçekleştirir. Başka bir [XmlReader](../xmlreader/) veya [XmlWriter](../xmlwriter/) nesnesini kapsıyorsanız, dış nesne ek bir uygunluk denetimi yapmaz. Uygunluk denetimi, altında yatan nesneye bırakılır. |
| Fragment | 1 | XML verileri, W3C tarafından tanımlandığı gibi bir [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities)'dır. Bu uygunluk seviyesi, kök öğesi olmayabilir ancak aksi takdirde iyi biçimlendirilmiş bir XML belgesini temsil eder. Bu denetim seviyesi, okunan veya yazılan akışın herhangi bir işlemci tarafından bir [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) olarak tüketilebilmesini sağlar. |
| Document | 2 | XML verileri, W3C tarafından tanımlandığı gibi iyi biçimlendirilmiş bir [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) için kurallara uyar. Bu denetim seviyesi, okunan veya yazılan akışın herhangi bir işlemci tarafından bir [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) olarak tüketilebilmesini sağlar. |

## Ayrıca Bakınız

* Ad Alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)