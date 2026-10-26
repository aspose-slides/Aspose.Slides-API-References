---
title: get_Current()
second_title: Aspose.Slides C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, bu XPathNodeIterator için XPathNavigator nesnesini alır ve geçerli bağlam düğümünde konumlandırır.
type: docs
weight: 1
url: /tr/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() metodu


Türetilmiş bir sınıfta geçersiz kılındığında, bu [XPathNodeIterator](../) için [XPathNavigator](../../xpathnavigator/) nesnesini alır ve geçerli bağlam düğümünde konumlandırır.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### Dönüş Değeri

Seçilen düğüm kümesinin alındığı bağlam düğümünde konumlandırılmış bir [XPathNavigator](../../xpathnavigator/) nesnesi. [XPathNodeIterator::MoveNext](../movenext/) yöntemi, [XPathNodeIterator](../) öğesini seçilen kümenin ilk düğümüne taşımak için çağrılmalıdır.

## Diğer Bağlantılar

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [XPathNavigator](../../xpathnavigator/)
* Sınıf [XPathNodeIterator](../)
* Ad Alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)