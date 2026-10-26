---
title: GetElementsByTagName()
second_title: Aspose.Slides dla C++ odniesienie API
description: "Zwraca XmlNodeList zawierającą listę wszystkich elementów potomnych, które pasują do określonego XmlElement::get_Name."
type: docs
weight: 287
url: /pl/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) metoda

Zwraca [XmlNodeList](../../xmlnodelist/) zawierający listę wszystkich elementów potomnych, które pasują do określonego [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tag nazwy do dopasowania. Jest to nazwa kwalifikowana. Jest dopasowywana do wartości **get_Name** węzła pasującego. Gwiazdka (*) jest specjalną wartością, która dopasowuje wszystkie tagi. |

### Wartość zwracana

[XmlNodeList](../../xmlnodelist/) zawierający listę wszystkich pasujących węzłów. Lista jest pusta, jeśli nie ma pasujących węzłów.

## XmlElement::GetElementsByTagName(String, String) metoda

Zwraca [XmlNodeList](../../xmlnodelist/) zawierający listę wszystkich elementów potomnych, które pasują do określonych wartości [XmlElement::get_LocalName](../get_localname/) i [XmlElement::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa do dopasowania. Gwiazdka (*) jest specjalną wartością, która dopasowuje wszystkie tagi. |
| namespaceURI | [String](../../../system/string/) | Namespace URI do dopasowania. |

### Wartość zwracana

[XmlNodeList](../../xmlnodelist/) zawierający listę wszystkich pasujących węzłów. Lista jest pusta, jeśli nie ma pasujących węzłów.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNodeList](../../xmlnodelist/)
* Klasa [String](../../../system/string/)
* Klasa [XmlElement](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)