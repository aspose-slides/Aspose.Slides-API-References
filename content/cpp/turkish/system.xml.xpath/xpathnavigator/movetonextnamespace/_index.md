---
title: MoveToNextNamespace()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, XPathNavigator öğesini belirtilen XPathNamespaceScope ile eşleşen bir sonraki ad alanı düğümüne taşır.
type: docs
weight: 573
url: /tr/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) metodu

Türetilmiş bir sınıfta geçersiz kılındığında, [XPathNavigator](../) öğesini belirtilen XPathNamespaceScope ile eşleşen bir sonraki ad alanı düğümüne taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Namespace kapsamını tanımlayan bir XPathNamespaceScope değeri. |

### Dönüş Değeri

**true** eğer [XPathNavigator](../) bir sonraki ad alanı düğümüne başarılı bir şekilde taşınıyorsa; aksi takdirde **false**. **false** ise, [XPathNavigator](../) konumu değişmemiş olur.

## XPathNavigator::MoveToNextNamespace() metodu

[XPathNavigator](../) öğesini bir sonraki ad alanı düğümüne taşır.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### Dönüş Değeri

**true** eğer [XPathNavigator](../) bir sonraki ad alanı düğümüne başarılı bir şekilde taşınıyorsa; aksi takdirde **false**. **false** ise, [XPathNavigator](../) konumu değişmemiş olur.

## Ayrıca Bakınız

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)