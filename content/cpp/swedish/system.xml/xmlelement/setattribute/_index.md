---
title: SetAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Anger värdet för attributet med det angivna namnet.
type: docs
weight: 222
url: /sv/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) method


Anger värdet för attributet med det angivna namnet.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet på attributet som ska skapas eller ändras. Detta är ett kvalificerat namn. Om namnet innehåller ett kolon parseras det till prefix- och lokala namnkomponenter. |
| value | [String](../../../system/string/) | Värdet som ska sättas för attributet. |

## XmlElement::SetAttribute(String, String, String) method


Anger värdet för attributet med det angivna lokala namnet och namnrymds-URI:n.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Namnrymdens URI för attributet. |
| value | [String](../../../system/string/) | Värdet som ska sättas för attributet. |

### Return Value

Attributvärdet.

## See Also

* Klass [String](../../../system/string/)
* Klass [XmlElement](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)