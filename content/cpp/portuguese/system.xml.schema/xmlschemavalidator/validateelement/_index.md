---
title: ValidateElement()
second_title: Referência da API Aspose.Slides para C++
description: Valida o elemento no contexto atual.
type: docs
weight: 131
url: /pt/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) método


Valida o elemento no contexto atual.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do elemento a ser validado. |
| namespaceUri | const [String](../../../system/string/)\& | O URI do namespace do elemento a ser validado. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Um objeto [XmlSchemaInfo](../../xmlschemainfo/) cujas propriedades são definidas após a validação bem-sucedida do nome do elemento. Este parâmetro pode ser **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) método


Valida o elemento no contexto atual com os valores dos atributos **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** e **xsi:NoNamespaceSchemaLocation** especificados.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do elemento a ser validado. |
| namespaceUri | const [String](../../../system/string/)\& | O URI do namespace do elemento a ser validado. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Um objeto [XmlSchemaInfo](../../xmlschemainfo/) cujas propriedades são definidas após a validação bem-sucedida do nome do elemento. Este parâmetro pode ser **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | O valor do atributo **xsi:Type** do elemento. Este parâmetro pode ser **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | O valor do atributo **xsi:Nil** do elemento. Este parâmetro pode ser **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | O valor do atributo **xsi:SchemaLocation** do elemento. Este parâmetro pode ser **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | O valor do atributo **xsi:NoNamespaceSchemaLocation** do elemento. Este parâmetro pode ser **nullptr**. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)