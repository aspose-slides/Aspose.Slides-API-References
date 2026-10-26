---
title: MoveToNext()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando viene sovrascritto in una classe derivata, sposta lo XPathNavigator al nodo fratello successivo del nodo corrente.
type: docs
weight: 586
url: /it/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() metodo

Quando viene sovrascritto in una classe derivata, sposta il [XPathNavigator](../) al nodo fratello successivo del nodo corrente.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### Valore restituito

**true** se il [XPathNavigator](../) riesce a spostarsi al nodo fratello successivo; altrimenti **false** se non ci sono più fratelli o se il [XPathNavigator](../) è attualmente posizionato su un nodo attributo. Se **false**, la posizione del [XPathNavigator](../) rimane invariata.

## XPathNavigator::MoveToNext(String, String) metodo

Sposta il [XPathNavigator](../) al nodo fratello successivo con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale del nodo fratello successivo verso cui spostarsi. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi del nodo fratello successivo verso cui spostarsi. |

### Valore restituito

**true** se il [XPathNavigator](../) è riuscito a spostarsi al nodo fratello successivo; **false** se non ci sono più fratelli, o se il [XPathNavigator](../) è attualmente posizionato su un nodo attributo. Se **false**, la posizione del [XPathNavigator](../) rimane invariata.

## XPathNavigator::MoveToNext(XPathNodeType) metodo

Sposta il [XPathNavigator](../) al nodo fratello successivo del nodo corrente che corrisponde al XPathNodeType specificato.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Il XPathNodeType del nodo fratello verso cui spostarsi. |

### Valore restituito

**true** se il [XPathNavigator](../) è riuscito a spostarsi al nodo fratello successivo; altrimenti, **false** se non ci sono più fratelli o se il [XPathNavigator](../) è attualmente posizionato su un nodo attributo. Se **false**, la posizione del [XPathNavigator](../) rimane invariata.

## Vedi anche

* Enum [XPathNodeType](../../xpathnodetype/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)