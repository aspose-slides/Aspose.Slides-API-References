---
title: ReadToNextSibling()
second_title: Aspose.Slides för C++ API-referens
description: Flyttar XmlReader till nästa syskonelement med det specificerade kvalificerade namnet.
type: docs
weight: 924
url: /sv/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) metod

Flyttar [XmlReader](../) till nästa syskonelement med det specificerade kvalificerade namnet.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på det syskonelement du vill flytta till. |

### Returvärde

**true** om ett matchande syskonelement hittas; annars **false**. Om ett matchande syskonelement inte hittas, är [XmlReader](../) placerad på sluttaggen ([XmlReader::get_NodeType](../get_nodetype/)-värdet är [XmlNodeType::EndElement](../../xmlnodetype/)) för föräldraelementet.

## XmlReader::ReadToNextSibling(String, String) metod

Flyttar [XmlReader](../) till nästa syskonelement med det specificerade lokala namnet och namnrymds-URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på det syskonelement du vill flytta till. |
| namespaceURI | [String](../../../system/string/) | Namnutrymmet URI för det syskonelement du vill flytta till. |

### Returvärde

**true** om ett matchande syskonelement hittas; annars **false**. Om ett matchande syskonelement inte hittas, är [XmlReader](../) placerad på sluttaggen ([XmlReader::get_NodeType](../get_nodetype/)-värdet är [XmlNodeType::EndElement](../../xmlnodetype/)) för föräldraelementet.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)