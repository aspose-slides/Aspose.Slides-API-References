---
title: GetNamespacesInScope()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce una raccolta di nomi di spazio dei nomi indicizzati per prefisso che può essere usata per enumerare gli spazi dei nomi attualmente nel contesto.
type: docs
weight: 105
url: /it/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) metodo

Restituisce una raccolta di nomi di spazio dei nomi indicizzati per prefisso che può essere usata per enumerare gli spazi dei nomi attualmente nel contesto.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Un valore di enumerazione che specifica il tipo di nodi di spazio dei nomi da restituire. |

### Valore restituito

Una raccolta di coppie spazio dei nomi e prefisso attualmente nel contesto.

## Vedi anche

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)