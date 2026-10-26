---
title: InsertAfter()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta el atributo especificado inmediatamente después del atributo de referencia especificado.
type: docs
weight: 66
url: /es/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) método

Inserta el atributo especificado inmediatamente después del atributo de referencia especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | El atributo a insertar. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | El atributo de referencia. **newNode** se coloca después del **refNode**. |

### Valor devuelto

El [XmlAttribute](../../xmlattribute/) para insertar en la colección.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlAttribute](../../xmlattribute/)
* Clase [XmlAttributeCollection](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)