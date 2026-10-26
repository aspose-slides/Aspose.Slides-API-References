---
title: XPathNodeType
second_title: Aspose.Slides for C++ API Referansı
description: XPathNavigator sınıfından döndürülebilecek XPath düğüm türlerini tanımlar.
type: docs
weight: 157
url: /tr/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

[XPath](../) düğüm türlerini tanımlar; bu türler [XPathNavigator](../xpathnavigator/) sınıfı tarafından döndürülebilir.

```cpp
enum class XPathNodeType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Root | 0 | XML belgesinin veya düğüm ağacının kök düğümü. |
| Element | 1 | Bir öğe, örneğin **<element>**. |
| Attribute | 2 | Bir öznitelik, örneğin **id='123'**. |
| Namespace | 3 | Bir ad alanı, örneğin **xmlns=\"namespace\"**. |
| Text | 4 | Bir düğümün metin içeriği. Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) ve CDATA düğüm türlerine eşdeğerdir. En az bir karakter içerir. |
| SignificantWhitespace | 5 | Beyaz boşluk karakterleri içeren ve **xml:space** **preserve** olarak ayarlanmış bir düğüm. |
| Whitespace | 6 | Yalnızca beyaz boşluk karakterleri içeren ve anlamlı boşluk bulunmayan bir düğüm. Beyaz boşluk karakterleri **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Bir işleme talimatı, örneğin **<?pi test?>**. Bu, [XPathNavigator](../xpathnavigator/) sınıfı tarafından görülemeyen XML bildirimlerini içermez. |
| Comment | 8 | Bir yorum, örneğin ****. |
| All | 9 | XPathNodeType düğüm türlerinden herhangi biri. |

## Ayrıca Bakınız

* Ad Alanı [System::Xml::XPath](../)
* Kütüphane [Aspose.Slides](../../)