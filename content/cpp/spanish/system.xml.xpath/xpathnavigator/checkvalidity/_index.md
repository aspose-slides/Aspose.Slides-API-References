---
title: CheckValidity()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica que los datos XML en el XPathNavigator cumplan con el lenguaje de definición de esquemas XML (XSD) proporcionado.
type: docs
weight: 755
url: /es/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) método

Verifica que los datos XML en el [XPathNavigator](../) cumplan con el lenguaje de definición XML [Schema](../../../system.xml.schema/) (XSD) proporcionado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | El XmlSchemaSet que contiene los esquemas usados para validar los datos XML contenidos en el [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | El ValidationEventHandler que recibe información sobre advertencias y errores de validación del esquema. |

### Valor devuelto

**true** si no se produjeron errores de validación del esquema; de lo contrario, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Clase [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)