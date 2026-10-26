---
title: GetNamespacesInScope()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en samling som innehåller alla namnrymder som för närvarande är i scope.
type: docs
weight: 716
url: /sv/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) metod


Returnerar en samling som innehåller alla namnrymder som för närvarande är i scope.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Ett XmlNamespaceScope-värde som anger typen av namnrymdsnoder som ska returneras. |

### Returvärde

Ett IDictionary-objekt som innehåller alla nuvarande namnrymder i scope. Om läsaren inte är placerad på ett element returneras en tom dictionary (inga namnrymder).

## Se också

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDictionary](../../../system.collections.generic/idictionary/)
* Klass [String](../../../system/string/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)