---
title: idx_get()
second_title: Aspose.Slides for C++ – dokumentacja API
description: "Zwraca pierwszy element potomny o podanej nazwie określonej przez XmlNode::get_Name."
type: docs
weight: 586
url: /pl/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) metoda

Zwraca pierwszy element potomny o określonym [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa elementu do pobrania. |

### Wartość zwracana

Pierwszy [XmlElement](../../xmlelement/) pasujący do określonej nazwy. Zwraca **nullptr**, jeśli nie ma dopasowania.

## XmlNode::idx_get(String, String) metoda

Zwraca pierwszy element potomny o określonych wartościach [XmlNode::get_LocalName](../get_localname/) i [XmlNode::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Lokalna nazwa elementu. |
| ns | [String](../../../system/string/) | URI przestrzeni nazw elementu. |

### Wartość zwracana

Pierwszy [XmlElement](../../xmlelement/) z pasującymi **localname** i **ns**. Zwraca **nullptr**, jeśli nie ma dopasowania.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlElement](../../xmlelement/)
* Klasa [String](../../../system/string/)
* Klasa [XmlNode](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)