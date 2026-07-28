---
title: ValueAs()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja az elem értékét a megadott típusban.
type: docs
weight: 131
url: /hu/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) metódus


Visszaadja az elem értékét a megadott típusban.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Az a típus, amelyben vissza kell adni az elem értékét. |

### Visszatérési érték

Az elem értéke a kért típusban.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metódus


Amikor egy származtatott osztályban felülírják, visszaadja az elem értékét a [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum által megadott típusban, amely a névtér előtagok feloldására szolgál.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Az a típus, amelyben vissza kell adni az elem értékét. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | A [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum, amely a névtér előtagok feloldására szolgál. |

### Visszatérési érték

Az elem értéke a kért típusban.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)