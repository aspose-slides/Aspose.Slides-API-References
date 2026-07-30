---
title: ReadNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un oggetto XmlNode basato sulle informazioni nel XmlReader. Il lettore deve essere posizionato su un nodo o attributo.
type: docs
weight: 495
url: /it/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) metodo

Crea un oggetto [XmlNode](../../xmlnode/) basato sulle informazioni nel [XmlReader](../../xmlreader/). Il reader deve essere posizionato su un nodo o attributo.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | La sorgente XML. |

### Valore restituito

Il nuovo [XmlNode](../../xmlnode/) o **nullptr** se non esistono altri nodi.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlReader](../../xmlreader/)
* Classe [XmlDocument](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)