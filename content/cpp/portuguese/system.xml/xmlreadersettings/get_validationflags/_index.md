---
title: get_ValidationFlags()
second_title: Referência da API Aspose.Slides para C++
description: "Retorna um valor que indica as configurações de validação de esquema. Esta configuração se aplica a objetos XmlReader que validam esquemas (XmlReaderSettings::get_ValidationType valor é ValidationType::Schema)."
type: docs
weight: 378
url: /pt/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() método


Retorna um valor que indica as configurações de validação de esquema. Esta configuração se aplica a objetos [XmlReader](../../xmlreader/) que validam esquemas (o valor [XmlReaderSettings::get_ValidationType](../get_validationtype/) é [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### Valor de Retorno

Uma combinação bit a bit de valores de enumeração que especificam as opções de validação. XmlSchemaValidationFlags::ProcessIdentityConstraints e XmlSchemaValidationFlags::AllowXmlAttributes estão habilitados por padrão. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation e XmlSchemaValidationFlags::ReportValidationWarnings estão desabilitados por padrão.

## Veja Também

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Classe [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)