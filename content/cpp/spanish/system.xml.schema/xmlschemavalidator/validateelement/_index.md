---
title: ValidateElement()
second_title: Referencia de API de Aspose.Slides para C++
description: Valida el elemento en el contexto actual.
type: docs
weight: 131
url: /es/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) método


Valida el elemento en el contexto actual.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | El nombre local del elemento a validar. |
| namespaceUri | const [String](../../../system/string/)\& | El URI del espacio de nombres del elemento a validar. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen al validar con éxito el nombre del elemento. Este parámetro puede ser **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) método


Valida el elemento en el contexto actual con los valores de los atributos **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** y **xsi:NoNamespaceSchemaLocation** especificados.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | El nombre local del elemento a validar. |
| namespaceUri | const [String](../../../system/string/)\& | El URI del espacio de nombres del elemento a validar. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen al validar con éxito el nombre del elemento. Este parámetro puede ser **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | El valor del atributo **xsi:Type** del elemento. Este parámetro puede ser **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | El valor del atributo **xsi:Nil** del elemento. Este parámetro puede ser **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | El valor del atributo **xsi:SchemaLocation** del elemento. Este parámetro puede ser **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | El valor del atributo **xsi:NoNamespaceSchemaLocation** del elemento. Este parámetro puede ser **nullptr**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [XmlSchemaInfo](../../xmlschemainfo/)
* Clase [XmlSchemaValidator](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)