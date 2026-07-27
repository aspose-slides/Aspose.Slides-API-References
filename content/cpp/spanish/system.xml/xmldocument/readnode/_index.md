---
title: ReadNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un objeto XmlNode basado en la información del XmlReader. El lector debe estar posicionado en un nodo o atributo.
type: docs
weight: 495
url: /es/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) method

Crea un objeto [XmlNode](../../xmlnode/) basado en la información del [XmlReader](../../xmlreader/). El lector debe estar posicionado en un nodo o atributo.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | La fuente XML. |

### Valor de retorno

El nuevo [XmlNode](../../xmlnode/) o **nullptr** si no existen más nodos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlReader](../../xmlreader/)
* Clase [XmlDocument](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)