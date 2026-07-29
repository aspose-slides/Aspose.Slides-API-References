---
title: RemoveAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort ett attribut efter namn.
type: docs
weight: 235
url: /sv/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) metod

Tar bort ett attribut efter namn.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet på attributet som ska tas bort. Detta är ett kvalificerat namn. Det matchas mot **get_Name**-värdet för den matchande noden. |

## XmlElement::RemoveAttribute(String, String) metod

Tar bort ett attribut med det angivna lokala namnet och namnrymds-URI. (Om det borttagna attributet har ett standardvärde ersätts det omedelbart).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet som ska tas bort. |
| namespaceURI | [String](../../../system/string/) | Namnrymds-URI för attributet som ska tas bort. |

## Se också

* Klass [String](../../../system/string/)
* Klass [XmlElement](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)