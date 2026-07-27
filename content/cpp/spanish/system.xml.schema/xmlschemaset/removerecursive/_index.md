---
title: RemoveRecursive()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina el esquema de lenguaje de definición XML Schema (XSD) especificado y todos los esquemas que éste importa del XmlSchemaSet.
type: docs
weight: 183
url: /es/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) método

Elimina el esquema [Schema](../../) de lenguaje de definición XML (XSD) especificado y todos los esquemas que éste importa del [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | El objeto [XmlSchema](../../xmlschema/) a eliminar del [XmlSchemaSet](../). |

### Valor devuelto

**true** si el objeto [XmlSchema](../../xmlschema/) y todas sus importaciones fueron eliminados correctamente; de lo contrario, **false**.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlSchema](../../xmlschema/)
* Clase [XmlSchemaSet](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)