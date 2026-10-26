---
title: GetNamespacesInScope()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una raccolta che contiene tutti gli spazi dei nomi attualmente in ambito.
type: docs
weight: 716
url: /it/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) metodo

Restituisce una raccolta che contiene tutti gli spazi dei nomi attualmente in ambito.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Un valore XmlNamespaceScope che specifica il tipo di nodi di spazio dei nomi da restituire. |

### Valore di ritorno

Un oggetto IDictionary che contiene tutti gli spazi dei nomi attualmente in ambito. Se il lettore non è posizionato su un elemento, viene restituito un dizionario vuoto (senza spazi dei nomi).

## Vedi anche

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)