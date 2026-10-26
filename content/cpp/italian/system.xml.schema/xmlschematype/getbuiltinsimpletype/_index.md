---
title: GetBuiltInSimpleType()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un XmlSchemaSimpleType che rappresenta il tipo semplice incorporato del tipo semplice specificato dal nome qualificato.
type: docs
weight: 183
url: /it/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) metodo


Restituisce un [XmlSchemaSimpleType](../../xmlschemasimpletype/) che rappresenta il tipo semplice incorporato del tipo semplice specificato dal nome qualificato.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | Il [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) del tipo semplice. |

### Valore di ritorno

Il [XmlSchemaSimpleType](../../xmlschemasimpletype/) che rappresenta il tipo semplice incorporato.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) metodo


Restituisce un [XmlSchemaSimpleType](../../xmlschemasimpletype/) che rappresenta il tipo semplice incorporato del tipo semplice specificato.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Uno dei valori XmlTypeCode che rappresentano il tipo semplice. |

### Valore di ritorno

Il [XmlSchemaSimpleType](../../xmlschemasimpletype/) che rappresenta il tipo semplice incorporato.

## See Also

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)