---
title: ValueAs()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert des Elements als den angegebenen Typ zurück.
type: docs
weight: 131
url: /de/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) Methode

Gibt den Wert des Elements als den angegebenen Typ zurück.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ, in dem der Elementwert zurückgegeben werden soll. |

### Rückgabewert

Der Wert des Elements als der angeforderte Typ.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) Methode

Wenn in einer abgeleiteten Klasse überschrieben, gibt sie den Wert des Elements als den mit dem [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt angegebenen Typ zurück, das zum Auflösen von Namespace-Präfixen verwendet wird.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ, in dem der Elementwert zurückgegeben werden soll. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt, das zum Auflösen von Namespace-Präfixen verwendet wird. |

### Rückgabewert

Der Wert des Elements als der angeforderte Typ.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XPathItem](../)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)