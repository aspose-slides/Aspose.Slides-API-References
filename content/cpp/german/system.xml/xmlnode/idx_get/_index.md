---
title: idx_get()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt das erste untergeordnete Element mit dem angegebenen XmlNode::get_Name zurück."
type: docs
weight: 586
url: /de/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) Methode

Gibt das erste untergeordnete Element mit dem angegebenen [XmlNode::get_Name](../get_name/) zurück.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des abzurufenden Elements. |

### Rückgabewert

Das erste [XmlElement](../../xmlelement/), das dem angegebenen Namen entspricht. Es gibt **nullptr** zurück, wenn keine Übereinstimmung vorhanden ist.

## XmlNode::idx_get(String, String) Methode

Gibt das erste untergeordnete Element mit den angegebenen [XmlNode::get_LocalName](../get_localname/)- und [XmlNode::get_NamespaceURI](../get_namespaceuri/)-Werten zurück.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Der lokale Name des Elements. |
| ns | [String](../../../system/string/) | Der Namespace-URI des Elements. |

### Rückgabewert

Das erste [XmlElement](../../xmlelement/) mit dem passenden **localname** und **ns**. Es gibt **nullptr** zurück, wenn keine Übereinstimmung vorhanden ist.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlElement](../../xmlelement/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNode](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)