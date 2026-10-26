---
title: ReadToFollowing()
second_title: Aspose.Slides för C++ API-referens
description: Läser tills ett element med det angivna kvalificerade namnet hittas.
type: docs
weight: 898
url: /sv/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) metod


Läser tills ett element med det angivna kvalificerade namnet hittas.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på elementet. |

### Returvärde

**true** om ett matchande element hittas; annars **false** och [XmlReader](../) är i ett EOF-tillstånd.

## XmlReader::ReadToFollowing(String, String) metod


Läser tills ett element med det angivna lokala namnet och namespace-URI hittas.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på elementet. |
| namespaceURI | [String](../../../system/string/) | Namespace-URI för elementet. |

### Returvärde

**true** om ett matchande element hittas; annars **false** och [XmlReader](../) är i ett EOF-tillstånd.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)