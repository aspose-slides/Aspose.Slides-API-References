---
title: GetElementsByTagName()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine XmlNodeList zurück, die eine Liste aller untergeordneten Elemente enthält, die dem angegebenen Namen entsprechen.
type: docs
weight: 443
url: /de/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) Methode

Gibt ein [XmlNodeList](../../xmlnodelist/) zurück, das eine Liste aller untergeordneten Elemente enthält, die dem angegebenen Namen entsprechen.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name, nach dem gesucht werden soll. Er wird mit dem **get_Name**-Wert des passenden Knotens verglichen. Der Sonderwert **"*"** entspricht allen Tags. |

### Rückgabewert

Ein [XmlNodeList](../../xmlnodelist/), das eine Liste aller passenden Knoten enthält. Wenn keine Knoten mit **name** übereinstimmen, ist die zurückgegebene Sammlung leer.

## XmlDocument::GetElementsByTagName(String, String) Methode

Gibt ein [XmlNodeList](../../xmlnodelist/) zurück, das eine Liste aller untergeordneten Elemente enthält, die den angegebenen [XmlDocument::get_LocalName](../get_localname/) und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) entsprechen.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der zu suchende LocalName. Der Sonderwert **"*"** entspricht allen Tags. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI, nach dem gesucht werden soll. |

### Rückgabewert

Ein [XmlNodeList](../../xmlnodelist/), das eine Liste aller passenden Knoten enthält. Wenn keine Knoten dem angegebenen **localName** und **namespaceURI** entsprechen, ist die zurückgegebene Sammlung leer.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNodeList](../../xmlnodelist/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)