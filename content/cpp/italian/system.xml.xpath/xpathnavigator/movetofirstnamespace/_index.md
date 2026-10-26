---
title: MoveToFirstNamespace()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, sposta l'XPathNavigator al primo nodo namespace che corrisponde allo XPathNamespaceScope specificato.
type: docs
weight: 560
url: /it/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) metodo


Quando sovrascritto in una classe derivata, sposta il [XPathNavigator](../) al primo nodo namespace che corrisponde allo XPathNamespaceScope specificato.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Un valore XPathNamespaceScope che descrive l&#39;ambito del namespace. |

### Valore restituito

**true** se il [XPathNavigator](../) riesce a spostarsi al primo nodo namespace; altrimenti, **false**. Se **false**, la posizione del [XPathNavigator](../) rimane invariata.

## XPathNavigator::MoveToFirstNamespace() metodo


Sposta il [XPathNavigator](../) al primo nodo namespace del nodo corrente.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```


### Valore restituito

**true** se il [XPathNavigator](../) riesce a spostarsi al primo nodo namespace; altrimenti, **false**. Se **false**, la posizione del [XPathNavigator](../) rimane invariata.

## Vedi anche

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)