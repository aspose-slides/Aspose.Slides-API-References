---
title: ReadStartElement()
second_title: Aspose.Slides C++ API-referencia
description: Ellenőrzi, hogy a jelenlegi csomópont egy elem, és a olvasót a következő csomópontra lépteti.
type: docs
weight: 846
url: /hu/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() metódus

Ellenőrzi, hogy a jelenlegi csomópont egy elem, és a olvasót a következő csomópontra lépteti.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) metódus

Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy elem-e a megadott [XmlReader::get_Name](../get_name/) értékkel, és a olvasót a következő csomópontra lépteti.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az elem minősített neve. |

## XmlReader::ReadStartElement(String, String) metódus

Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy elem-e a megadott [XmlReader::get_LocalName](../get_localname/) és [XmlReader::get_NamespaceURI](../get_namespaceuri/) értékekkel, és a olvasót a következő csomópontra lépteti.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Az elem helyi neve. |
| ns | [String](../../../system/string/) | Az elem névtér URI-ja. |

## Lásd még

* Osztály [XmlReader](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)