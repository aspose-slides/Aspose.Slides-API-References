---
title: get_Attributes()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce una XmlAttributeCollection contenente gli attributi di questo nodo.
type: docs
weight: 105
url: /it/system.xml/xmlnode/get_attributes/
---
## XmlNode::get_Attributes() metodo

Restituisce un [XmlAttributeCollection](../../xmlattributecollection/) contenente gli attributi di questo nodo.

```cpp
virtual SharedPtr<XmlAttributeCollection> System::Xml::XmlNode::get_Attributes() final
```

### Valore di ritorno

Un [XmlAttributeCollection](../../xmlattributecollection/) contenente gli attributi del nodo. Se il nodo è del tipo [XmlNodeType::Element](../../xmlnodetype/), vengono restituiti gli attributi del nodo. Altrimenti, questo metodo restituisce **nullptr**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttributeCollection](../../xmlattributecollection/)
* Classe [XmlNode](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)