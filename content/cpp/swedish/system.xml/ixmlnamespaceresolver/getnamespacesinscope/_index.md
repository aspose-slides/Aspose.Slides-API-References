---
title: GetNamespacesInScope()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en samling av definierade prefix-namnrymdsmappningar som för närvarande är i räckvidd.
type: docs
weight: 1
url: /sv/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) metod


Returnerar en samling av definierade prefix-namnrymdsmappningar som för närvarande är i räckvidd.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Ett XmlNamespaceScope-värde som anger typen av namnrymdsnoder som ska returneras. |

### Returvärde

En IDictionary-samling som innehåller de aktuella namnrymderna i räckvidd.

## Se även

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDictionary](../../../system.collections.generic/idictionary/)
* Klass [String](../../../system/string/)
* Klass [IXmlNamespaceResolver](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)