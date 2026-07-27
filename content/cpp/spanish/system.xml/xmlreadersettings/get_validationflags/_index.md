---
title: get_ValidationFlags()
second_title: Referencia de API de Aspose.Slides para C++
description: "Devuelve un valor que indica la configuración de validación de esquemas. Esta configuración se aplica a los objetos XmlReader que validan esquemas (el valor XmlReaderSettings::get_ValidationType es ValidationType::Schema)."
type: docs
weight: 378
url: /es/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() método

Devuelve un valor que indica la configuración de validación de esquemas. Esta configuración se aplica a los objetos [XmlReader](../../xmlreader/) que validan esquemas (el valor [XmlReaderSettings::get_ValidationType](../get_validationtype/) es [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### Valor de retorno

Una combinación bit a bit de valores de enumeración que especifican opciones de validación. XmlSchemaValidationFlags::ProcessIdentityConstraints y XmlSchemaValidationFlags::AllowXmlAttributes están habilitados por defecto. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation y XmlSchemaValidationFlags::ReportValidationWarnings están deshabilitados por defecto.

## Ver también

* Enumeración [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Clase [XmlReaderSettings](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)