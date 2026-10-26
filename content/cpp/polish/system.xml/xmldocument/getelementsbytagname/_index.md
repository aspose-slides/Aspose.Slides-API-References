---
title: GetElementsByTagName()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca XmlNodeList zawierający listę wszystkich elementów potomnych, które pasują do określonej nazwy.
type: docs
weight: 443
url: /pl/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) metoda

Zwraca [XmlNodeList](../../xmlnodelist/) zawierający listę wszystkich elementów potomnych, które pasują do określonej nazwy.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Właściwa nazwa do dopasowania. Jest dopasowywana do wartości **get_Name** węzła dopasowanego. Specjalna wartość **"*"`** dopasowuje wszystkie znaczniki. |

### Wartość zwracana

[XmlNodeList](../../xmlnodelist/) zawierający listę wszystkich pasujących węzłów. Jeśli żaden węzeł nie pasuje do **name**, zwrócona kolekcja będzie pusta.

## XmlDocument::GetElementsByTagName(String, String) metoda

Zwraca [XmlNodeList](../../xmlnodelist/) zawierający listę wszystkich elementów potomnych, które pasują do określonych [XmlDocument::get_LocalName](../get_localname/) i [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa LocalName do dopasowania. Specjalna wartość **"*"`** dopasowuje wszystkie znaczniki. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI do dopasowania. |

### Wartość zwracana

[XmlNodeList](../../xmlnodelist/) zawierający listę wszystkich pasujących węzłów. Jeśli żaden węzeł nie pasuje do określonych **localName** i **namespaceURI**, zwrócona kolekcja będzie pusta.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNodeList](../../xmlnodelist/)
* Klasa [String](../../../system/string/)
* Klasa [XmlDocument](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)