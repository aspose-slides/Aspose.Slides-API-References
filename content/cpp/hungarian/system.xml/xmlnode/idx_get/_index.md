---
title: idx_get()
second_title: Aspose.Slides C++ API referencia
description: "Visszaadja az első gyermekelemet a megadott XmlNode::get_Name alapján."
type: docs
weight: 586
url: /hu/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) metódus


Visszaadja az első gyermekelemet a megadott [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az lekérdezendő elem minősített neve. |

### Visszatérési érték

Az első [XmlElement](../../xmlelement/) amely megfelel a megadott névnek. Visszaadja **nullptr**-t, ha nincs egyezés.

## XmlNode::idx_get(String, String) metódus


Visszaadja az első gyermekelemet a megadott [XmlNode::get_LocalName](../get_localname/) és [XmlNode::get_NamespaceURI](../get_namespaceuri/) értékekkel.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Az elem helyi neve. |
| ns | [String](../../../system/string/) | Az elem névtere URI-ja. |

### Visszatérési érték

Az első [XmlElement](../../xmlelement/) amely megfelel a **localname** és **ns** értékeknek. Visszaadja **nullptr**-t, ha nincs egyezés.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)