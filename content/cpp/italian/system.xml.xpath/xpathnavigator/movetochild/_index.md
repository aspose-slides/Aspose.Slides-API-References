---
title: MoveToChild()
second_title: Riferimento API Aspose.Slides per C++
description: Sposta lo XPathNavigator sul nodo figlio con il nome locale e l'URI dello spazio dei nomi specificati.
type: docs
weight: 690
url: /it/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) metodo

Sposta il [XPathNavigator](../) sul nodo figlio con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale del nodo figlio a cui spostarsi. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi del nodo figlio a cui spostarsi. |

### Valore di ritorno

**true** se il [XPathNavigator](../) riesce a spostarsi sul nodo figlio; altrimenti, **false**. Se **false**, la posizione del [XPathNavigator](../) rimane invariata.

## XPathNavigator::MoveToChild(XPathNodeType) metodo

Sposta il [XPathNavigator](../) sul nodo figlio del XPathNodeType specificato.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Il XPathNodeType del nodo figlio a cui spostarsi. |

### Valore di ritorno

**true** se il [XPathNavigator](../) riesce a spostarsi sul nodo figlio; altrimenti, **false**. Se **false**, la posizione del [XPathNavigator](../) rimane invariata.

## Vedi anche

* Enum [XPathNodeType](../../xpathnodetype/)
* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)