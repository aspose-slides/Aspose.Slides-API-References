---
title: CloneNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un duplicato di questo nodo.
type: docs
weight: 157
url: /it/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) method

Crea un duplicato di questo nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso. Poiché i nodi [XmlDeclaration](../) non hanno figli, il nodo clonato include sempre il valore dei dati, indipendentemente dall’impostazione del parametro. |

### Valore restituito

Il nodo clonato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlDeclaration](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)