---
title: GetNamespacesInScope()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una raccolta di mapping prefisso-spazio dei nomi definiti che sono attualmente in ambito.
type: docs
weight: 1
url: /it/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) metodo

Restituisce una raccolta di mapping prefisso-spazio dei nomi definiti che sono attualmente in ambito.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Un valore XmlNamespaceScope che specifica il tipo di nodi di spazio dei nomi da restituire. |

### Valore di ritorno

Una collezione IDictionary che contiene gli spazi dei nomi attualmente in ambito.

## Vedi anche

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)