---
title: CloneNode()
second_title: Aspose.Slides per C++ Riferimento API
description: Crea un duplicato di questo nodo.
type: docs
weight: 196
url: /it/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode(bool) metodo

Crea un duplicato di questo nodo.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | **bool** | **true** per clonare ricorsivamente il sottoalbero sotto il nodo specificato; **false** per clonare solo il nodo stesso (e i suoi attributi se il nodo è un [XmlElement](../)). |

### Valore restituito

Il nodo clonato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlElement](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)