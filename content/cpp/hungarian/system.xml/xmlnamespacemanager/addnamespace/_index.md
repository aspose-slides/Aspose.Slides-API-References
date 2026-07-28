---
title: AddNamespace()
second_title: Aspose.Slides a C++ API hivatkozása
description: Hozzáadja a megadott névteret a gyűjteményhez.
type: docs
weight: 66
url: /hu/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) metódus

Hozzáadja a megadott névteret a gyűjteményhez.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | A hozzáadandó névtérhez társítandó előtag. Használja a [String::Empty](../../../system/string/empty/)-t egy alapértelmezett névtér hozzáadásához. Ha a [XmlNamespaceManager](../) egy XML Path Language ([XPath](../../../system.xml.xpath/)) kifejezésben lesz használva a névterek feloldásához, akkor meg kell adni egy előtagot. Ha egy [XPath](../../../system.xml.xpath/) kifejezés nem tartalmaz előtagot, akkor feltételezzük, hogy a névtér Uniform Resource Identifier (URI) az üres névtér. További információért a [XPath](../../../system.xml.xpath/) kifejezésekkel és a [XmlNamespaceManager](../)-val kapcsolatban, tekintse meg az XmlNode::SelectNodes(String) és az XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) metódusokat. |
| uri | [String](../../../system/string/) | A hozzáadandó névtér. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNamespaceManager](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)