---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el XmlSchema asociado con el URI del espacio de nombres proporcionado.
type: docs
weight: 53
url: /es/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) método

Devuelve el [XmlSchema](../../xmlschema/) asociado con el URI del espacio de nombres especificado.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres asociado con el esquema que desea devolver. Normalmente será el **targetNamespace** del esquema. |

### Valor de retorno

El [XmlSchema](../../xmlschema/) asociado con el URI del espacio de nombres; **nullptr** si no hay un esquema cargado asociado con el espacio de nombres dado o si el espacio de nombres está asociado con un esquema XDR.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlSchema](../../xmlschema/)
* Clase [String](../../../system/string/)
* Clase [XmlSchemaCollection](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)