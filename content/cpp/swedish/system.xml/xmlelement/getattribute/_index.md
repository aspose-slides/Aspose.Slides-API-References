---
title: GetAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar värdet för attributet med det angivna namnet.
type: docs
weight: 209
url: /sv/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) metod

Returnerar värdet för attributet med det angivna namnet.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet på attributet som ska hämtas. Detta är ett kvalificerat namn. Det matchas mot **get_Name**-värdet för den matchande noden. |

### Returvärde

Värdet för det angivna attributet. En tom sträng returneras om ett matchande attribut inte hittas eller om attributet inte har ett angivet eller standardvärde.

## XmlElement::GetAttribute(String, String) metod

Returnerar värdet för attributet med det angivna lokala namnet och namnrymds-URI:n.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet som ska hämtas. |
| namespaceURI | [String](../../../system/string/) | Namnrymds-URI:n för attributet som ska hämtas. |

### Returvärde

Värdet för det angivna attributet. En tom sträng returneras om ett matchande attribut inte hittas eller om attributet inte har ett angivet eller standardvärde.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlElement](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)