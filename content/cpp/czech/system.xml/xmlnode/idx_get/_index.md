---
title: idx_get()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací první podřízený element se zadaným XmlNode::get_Name."
type: docs
weight: 586
url: /cs/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) metoda

Vrací první podřízený element se zadaným [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název elementu, který se má získat. |

### Návratová hodnota

První [XmlElement](../../xmlelement/) odpovídající zadanému názvu. Vrací **nullptr**, pokud neexistuje shoda.

## XmlNode::idx_get(String, String) metoda

Vrací první podřízený element se zadanými hodnotami [XmlNode::get_LocalName](../get_localname/) a [XmlNode::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Lokální název elementu. |
| ns | [String](../../../system/string/) | URI jmenného prostoru elementu. |

### Návratová hodnota

První [XmlElement](../../xmlelement/) s odpovídajícími **localname** a **ns**. Vrací **nullptr**, pokud neexistuje shoda.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlElement](../../xmlelement/)
* Třída [String](../../../system/string/)
* Třída [XmlNode](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)