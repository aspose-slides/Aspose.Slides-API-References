---
title: GetNamespacesInScope()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine Sammlung definierter Präfix-Namensraumzuordnungen zurück, die derzeit im Geltungsbereich liegen.
type: docs
weight: 1
url: /de/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) Methode


Gibt eine Sammlung von definierten Präfix-Namensraumzuordnungen zurück, die derzeit im Geltungsbereich liegen.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Ein XmlNamespaceScope-Wert, der den Typ der zurückzugebenden Namensraumknoten angibt. |

### Rückgabewert

Eine IDictionary-Sammlung, die die aktuellen im Geltungsbereich liegenden Namensräume enthält.

## Siehe auch

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [String](../../../system/string/)
* Klasse [IXmlNamespaceResolver](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)