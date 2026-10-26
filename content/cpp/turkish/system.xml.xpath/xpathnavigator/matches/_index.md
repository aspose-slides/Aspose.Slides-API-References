---
title: Matches()
second_title: Aspose.Slides C++ API Referansı için
description: Mevcut düğümün belirtilen XPathExpression ifadesiyle eşleşip eşleşmediğini belirler.
type: docs
weight: 820
url: /tr/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) metod


Mevcut düğümün belirtilen [XPathExpression](../../xpathexpression/) ile eşleşip eşleşmediğini belirler.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) nesnesi, derlenmiş [XPath](../../) ifadesini içerir. |

### Dönüş Değeri

**true** if the current node matches the [XPathExpression](../../xpathexpression/); otherwise, **false**.

## XPathNavigator::Matches(String) metod


Mevcut düğümün belirtilen [XPath](../../) ifadesiyle eşleşip eşleşmediğini belirler.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [XPath](../../) ifadesi. |

### Dönüş Değeri

Mevcut düğüm belirtilen [XPath](../../) ifadesiyle eşleşiyorsa **true**; aksi takdirde **false**.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XPathExpression](../../xpathexpression/)
* Sınıf [XPathNavigator](../)
* Sınıf [String](../../../system/string/)
* İsim Uzayı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)