---
title: AddNamespace()
second_title: Aspose.Slides for C++ API Referansı
description: Verilen ad alanını kümeye ekler.
type: docs
weight: 66
url: /tr/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) yöntemi

Adds the given namespace to the collection.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Eklenen ad alanı ile ilişkilendirilecek önek. Varsayılan bir ad alanı eklemek için [String::Empty](../../../system/string/empty/) kullanın. [XmlNamespaceManager](../) bir XML Path Language ([XPath](../../../system.xml.xpath/)) ifadesinde ad alanlarını çözmek için kullanılacaksa, bir önek belirtilmelidir. Bir [XPath](../../../system.xml.xpath/) ifadesi bir önek içermiyorsa, ad alanı Uniform Resource Identifier (URI) boş ad alanı olduğu varsayılır. [XPath](../../../system.xml.xpath/) ifadeleri ve [XmlNamespaceManager](../) hakkında daha fazla bilgi için XmlNode::SelectNodes(String) ve XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) yöntemlerine bakın. |
| uri | [String](../../../system/string/) | Eklenecek ad alanı. |

## Diğerlerine Bakın

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNamespaceManager](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)