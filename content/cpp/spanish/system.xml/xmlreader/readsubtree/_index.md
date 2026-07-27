---
title: ReadSubtree()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una nueva instancia de XmlReader que puede usarse para leer el nodo actual y todos sus descendientes.
type: docs
weight: 963
url: /es/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() método

Devuelve una nueva instancia de [XmlReader](../) que puede usarse para leer el nodo actual y todos sus descendientes.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### Valor de retorno

Una nueva instancia de lector XML configurada en [ReadState::Initial](../../readstate/). Llamar al método [XmlReader::Read](../read/) posiciona al nuevo lector en el nodo que era actual antes de la llamada al método [XmlReader::ReadSubtree](./).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)