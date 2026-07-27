---
title: InsertBefore()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta el nodo especificado inmediatamente antes del nodo de referencia especificado.
type: docs
weight: 209
url: /es/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) método

Inserta el nodo especificado inmediatamente antes del nodo de referencia especificado.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | El [XmlNode](../../xmlnode/) a insertar. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | El [XmlNode](../../xmlnode/) que es el nodo de referencia. El **newChild** se coloca antes de este nodo. |

### Valor devuelto

El [XmlNode](../../xmlnode/) insertado.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [XmlAttribute](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)