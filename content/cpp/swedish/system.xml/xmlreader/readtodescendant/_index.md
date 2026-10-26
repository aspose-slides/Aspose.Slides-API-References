---
title: ReadToDescendant()
second_title: Aspose.Slides för C++ API-referens
description: Avancerar XmlReader till nästa avkommande element med det angivna kvalificerade namnet.
type: docs
weight: 911
url: /sv/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) metod

Avancerar [XmlReader](../) till nästa avkommande element med det angivna kvalificerade namnet.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på elementet du vill flytta till. |

### Returvärde

**true** om ett matchande avkommande element hittas; annars **false**. Om ett matchande underordnat element inte hittas, positioneras [XmlReader](../) på sluttaggen ([XmlReader::get_NodeType](../get_nodetype/)-värdet är [XmlNodeType::EndElement](../../xmlnodetype/)) för elementet. Om [XmlReader](../) inte är positionerad på ett element när [XmlReader::ReadToDescendant(String)](./) anropas, returnerar denna metod **false** och positionen för [XmlReader](../) ändras inte.

## XmlReader::ReadToDescendant(String, String) metod

Avancerar [XmlReader](../) till nästa avkommande element med det angivna lokala namnet och namnutrymmet URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på elementet du vill flytta till. |
| namespaceURI | [String](../../../system/string/) | Namnutrymmet URI för elementet du vill flytta till. |

### Returvärde

**true** om ett matchande avkommande element hittas; annars **false**. Om ett matchande underordnat element inte hittas, positioneras [XmlReader](../) på sluttaggen ([XmlReader::get_NodeType](../get_nodetype/)-värdet är [XmlNodeType::EndElement](../../xmlnodetype/)) för elementet. Om [XmlReader](../) inte är positionerad på ett element när [XmlReader::ReadToDescendant(String,String)](./) anropas, returnerar denna metod **false** och positionen för [XmlReader](../) ändras inte.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)