---
title: XmlSchemaValidator()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase XmlSchemaValidator.
type: docs
weight: 92
url: /es/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor


Inicializa una nueva instancia de la clase [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Un objeto [XmlNameTable](../../../system.xml/xmlnametable/) que contiene nombres de elementos y atributos como cadenas atomizadas. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Un objeto [XmlSchemaSet](../../xmlschemaset/) que contiene los esquemas de Lenguaje de Definición XML [Schema](../../) (XSD) utilizados para la validación. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Un objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver los espacios de nombres encontrados durante la validación. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Un valor XmlSchemaValidationFlags que especifica las opciones de validación del esquema. |

## Véase también

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)