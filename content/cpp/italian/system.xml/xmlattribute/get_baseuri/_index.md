---
title: get_BaseURI()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'Uniform Resource Identifier (URI) di base del nodo.
type: docs
weight: 183
url: /it/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() metodo

Restituisce l'Uniform Resource Identifier (URI) di base del nodo.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```

### Valore di ritorno

La posizione da cui il nodo è stato caricato o [String::Empty](../../../system/string/empty/) se il nodo non ha un URI di base. [Attribute](../../../system/attribute/) nodi hanno lo stesso URI di base del loro elemento proprietario. Se un nodo attributo non ha un elemento proprietario, get_BaseURI restituisce [String::Empty](../../../system/string/empty/).

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlAttribute](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)