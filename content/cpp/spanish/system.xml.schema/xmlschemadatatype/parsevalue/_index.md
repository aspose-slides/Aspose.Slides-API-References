---
title: ParseValue()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, valida la cadena especificada contra un tipo simple incorporado o definido por el usuario.
type: docs
weight: 53
url: /es/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) método


When overridden in a derived class, validates the **string** specified against a built-in or user-defined simple type.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | [String](../../../system/string/) | El **string** a validar contra el tipo simple. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | El [XmlNameTable](../../../system.xml/xmlnametable/) a usar para la atomización mientras se analiza el **string** si este objeto [XmlSchemaDatatype](../) representa el tipo **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) a usar mientras se analiza el **string** si este objeto [XmlSchemaDatatype](../) representa el tipo **xs:QName**. |

### Valor devuelto

Un [Object](../../../system/object/) que puede convertirse de forma segura al tipo devuelto por la llamada [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [String](../../../system/string/)
* Clase [XmlNameTable](../../../system.xml/xmlnametable/)
* Clase [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Clase [XmlSchemaDatatype](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)