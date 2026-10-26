---
title: HasAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om den aktuella noden har ett attribut med det angivna namnet.
type: docs
weight: 300
url: /sv/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) metod


Bestämmer om den aktuella noden har ett attribut med det angivna namnet.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet på attributet att hitta. Detta är ett kvalificerat namn. Det matchas mot **get_Name**-värdet för den matchande noden. |

### Returvärde

**true** om den aktuella noden har det angivna attributet; annars **false**.

## XmlElement::HasAttribute(String, String) metod


Bestämmer om den aktuella noden har ett attribut med det angivna lokala namnet och namnrymds-URI.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet att hitta. |
| namespaceURI | [String](../../../system/string/) | Namnrymds-URI för attributet att hitta. |

### Returvärde

**true** om den aktuella noden har det angivna attributet; annars **false**.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlElement](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)