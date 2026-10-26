---
title: ReadStartElement()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar att den aktuella noden är ett element och flyttar läsaren till nästa nod.
type: docs
weight: 846
url: /sv/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() method

Kontrollerar att den aktuella noden är ett element och flyttar läsaren till nästa nod.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```
## XmlReader::ReadStartElement(String) method

Kontrollerar att den aktuella innehållsnoden är ett element med det angivna [XmlReader::get_Name](../get_name/)-värdet och flyttar läsaren till nästa nod.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```
### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det fullständiga namnet på elementet. |

## XmlReader::ReadStartElement(String, String) method

Kontrollerar att den aktuella innehållsnoden är ett element med de angivna [XmlReader::get_LocalName](../get_localname/)- och [XmlReader::get_NamespaceURI](../get_namespaceuri/)-värdena och flyttar läsaren till nästa nod.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```
### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Det lokala namnet på elementet. |
| ns | [String](../../../system/string/) | Namnområdets URI för elementet. |

## Se även

* Klass [XmlReader](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)