---
title: ValidateEndElement()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se o conteúdo de texto do elemento é válido de acordo com seu tipo de dados para elementos com conteúdo simples e verifica se o conteúdo do elemento atual está completo para elementos com conteúdo complexo.
type: docs
weight: 209
url: /pt/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) método


Verifica se o conteúdo de texto do elemento é válido de acordo com seu tipo de dados para elementos com conteúdo simples e verifica se o conteúdo do elemento atual está completo para elementos com conteúdo complexo.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Um objeto [XmlSchemaInfo](../../xmlschemainfo/) cujas propriedades são definidas após a validação bem-sucedida do elemento. Este parâmetro pode ser **nullptr**. |

### Valor de Retorno

O valor de texto analisado e tipado do elemento se o elemento possuir conteúdo simples.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) método


Verifica se o conteúdo de texto do elemento especificado é válido de acordo com seu tipo de dados.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Um objeto [XmlSchemaInfo](../../xmlschemainfo/) cujas propriedades são definidas após a validação bem-sucedida do conteúdo de texto do elemento. Este parâmetro pode ser **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | O conteúdo de texto tipado do elemento. |

### Valor de Retorno

O conteúdo simples tipado, analisado, do elemento.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XmlSchemaInfo](../../xmlschemainfo/)
* Classe [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)