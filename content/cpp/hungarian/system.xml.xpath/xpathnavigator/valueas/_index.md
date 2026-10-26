---
title: ValueAs()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja az aktuális csomópont értékét a megadott Type típusában, a névtér előtagok feloldásához megadott IXmlNamespaceResolver objektum használatával.
type: docs
weight: 378
url: /hu/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo&, SharedPtr<IXmlNamespaceResolver>) metódus

Visszaadja az aktuális csomópont értékét a megadott Type típusában, a(z) [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum használatával, amely a névtér-előtagok feloldására szolgál.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)& | Az a Type, amelyben az aktuális csomópont értékét visszaadja. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum, amely a névtér-előtagok feloldására szolgál. |

### Visszatérési érték

Az aktuális csomópont értéke a kért Type típusában.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Osztály [XPathNavigator](../)
* Névtér [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)