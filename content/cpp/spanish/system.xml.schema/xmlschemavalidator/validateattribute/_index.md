---
title: ValidateAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: Valida el nombre del atributo, el URI del espacio de nombres y el valor en el contexto del elemento actual.
type: docs
weight: 144
url: /es/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String&, const String&, const String&, const SharedPtr<XmlSchemaInfo>&) método

Valida el nombre del atributo, el URI del espacio de nombres y el valor en el contexto del elemento actual.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | El nombre local del atributo a validar. |
| namespaceUri | const [String](../../../system/string/)& | El URI del espacio de nombres del atributo a validar. |
| attributeValue | const [String](../../../system/string/)& | El valor del atributo a validar. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras la validación exitosa del atributo. Este parámetro puede ser **nullptr**. |

### Valor devuelto

El valor del atributo validado.

## XmlSchemaValidator::ValidateAttribute(const String&, const String&, XmlValueGetter, const SharedPtr<XmlSchemaInfo>&) método

Valida el nombre del atributo, el URI del espacio de nombres y el valor en el contexto del elemento actual.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)& | El nombre local del atributo a validar. |
| namespaceUri | const [String](../../../system/string/)& | El URI del espacio de nombres del atributo a validar. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Una devolución de llamada XmlValueGetter utilizada para pasar el valor del atributo como un tipo compatible con el lenguaje de definición XML [Schema](../../) (XSD) del atributo. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaInfo](../../xmlschemainfo/)>& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras la validación exitosa del atributo. Este parámetro puede ser **nullptr**. |

### Valor devuelto

El valor del atributo validado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Clase [Object](../../../system/object/)
* Clase [String](../../../system/string/)
* Clase [XmlSchemaInfo](../../xmlschemainfo/)
* Clase [XmlSchemaValidator](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)