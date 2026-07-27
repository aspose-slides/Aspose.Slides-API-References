---
title: ValidateAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Valida o nome do atributo, o URI do namespace e o valor no contexto do elemento atual.
type: docs
weight: 144
url: /pt/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) método


Valida o nome do atributo, o URI do namespace e o valor no contexto do elemento atual.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do atributo a ser validado. |
| namespaceUri | const [String](../../../system/string/)\& | O URI do namespace do atributo a ser validado. |
| attributeValue | const [String](../../../system/string/)\& | O valor do atributo a ser validado. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Um objeto [XmlSchemaInfo](../../xmlschemainfo/) cujas propriedades são definidas após a validação bem-sucedida do atributo. Este parâmetro pode ser **nullptr**. |

### Valor de Retorno

O valor do atributo validado.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) método


Valida o nome do atributo, o URI do namespace e o valor no contexto do elemento atual.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do atributo a ser validado. |
| namespaceUri | const [String](../../../system/string/)\& | O URI do namespace do atributo a ser validado. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Um callback XmlValueGetter usado para passar o valor do atributo como um tipo compatível com a Linguagem de Definição de XML [Schema](../../) (XSD) do atributo. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Um objeto [XmlSchemaInfo](../../xmlschemainfo/) cujas propriedades são definidas após a validação bem-sucedida do atributo. Este parâmetro pode ser **nullptr**. |

### Valor de Retorno

O valor do atributo validado.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaInfo](../../xmlschemainfo/)
* Classe [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)