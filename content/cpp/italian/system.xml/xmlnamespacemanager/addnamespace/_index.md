---
title: AddNamespace()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge lo spazio dei nomi fornito alla raccolta.
type: docs
weight: 66
url: /it/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) metodo

Aggiunge lo spazio dei nomi fornito alla raccolta.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Il prefisso da associare allo spazio dei nomi da aggiungere. Usa [String::Empty](../../../system/string/empty/) per aggiungere uno spazio dei nomi predefinito. Se il [XmlNamespaceManager](../) verrà utilizzato per risolvere gli spazi dei nomi in un'espressione XML Path Language ([XPath](../../../system.xml.xpath/)), è necessario specificare un prefisso. Se un'espressione [XPath](../../../system.xml.xpath/) non include un prefisso, si presume che l'Identificatore Uniforme di Risorsa (URI) dello spazio dei nomi sia lo spazio dei nomi vuoto. Per ulteriori informazioni sulle espressioni [XPath](../../../system.xml.xpath/) e su [XmlNamespaceManager](../), consulta i metodi XmlNode::SelectNodes(String) e XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>). |
| uri | [String](../../../system/string/) | Lo spazio dei nomi da aggiungere. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)