---
title: InferSchema()
second_title: Referencia de la API de Aspose.Slides para C++
description: Genera un esquema de XML Schema Definition Language (XSD) a partir del documento XML contenido en el objeto XmlReader especificado.
type: docs
weight: 66
url: /es/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) método

Infiera un esquema XML [Schema](../../) Definition Language (XSD) a partir del documento XML contenido en el objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un objeto [XmlReader](../../../system.xml/xmlreader/) que contiene el documento XML del cual inferir un esquema. |

### Valor devuelto

Un objeto [XmlSchemaSet](../../xmlschemaset/) que contiene los esquemas inferidos.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) método

Infiera un esquema XML [Schema](../../) Definition Language (XSD) a partir del documento XML contenido en el objeto [XmlReader](../../../system.xml/xmlreader/) especificado, y refina el esquema inferido utilizando un esquema existente en el objeto [XmlSchemaSet](../../xmlschemaset/) especificado con el mismo espacio de nombres de destino.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un objeto [XmlReader](../../../system.xml/xmlreader/) que contiene el documento XML del cual inferir un esquema. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Un objeto [XmlSchemaSet](../../xmlschemaset/) que contiene un esquema existente utilizado para refinar el esquema inferido. |

### Valor devuelto

Un objeto [XmlSchemaSet](../../xmlschemaset/) que contiene los esquemas inferidos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)