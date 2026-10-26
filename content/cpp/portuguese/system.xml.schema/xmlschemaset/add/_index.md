---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona o esquema da linguagem de definição XML Schema (XSD) no URL especificado ao XmlSchemaSet.
type: docs
weight: 157
url: /pt/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) método


Adiciona o esquema [Schema](../../) da linguagem de definição XML (XSD) no URL especificado ao [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | O valor **targetNamespace** do esquema, ou **nullptr** para usar o **targetNamespace** especificado no esquema. |
| schemaUri | const [String](../../../system/string/)\& | O URL que especifica o esquema a ser carregado. |

### Valor de retorno

Um objeto [XmlSchema](../../xmlschema/) se o esquema for válido. Se o esquema não for válido e um ValidationEventHandler for especificado, então **nullptr** é retornado e o evento de validação apropriado é disparado. Caso contrário, uma XmlSchemaException é lançada.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) método


Adiciona o esquema [Schema](../../) da linguagem de definição XML (XSD) contido no [XmlReader](../../../system.xml/xmlreader/) ao [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | O valor **targetNamespace** do esquema, ou **nullptr** para usar o **targetNamespace** especificado no esquema. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | O objeto [XmlReader](../../../system.xml/xmlreader/). |

### Valor de retorno

Um objeto [XmlSchema](../../xmlschema/) se o esquema for válido. Se o esquema não for válido e um ValidationEventHandler for especificado, então **nullptr** é retornado e o evento de validação apropriado é disparado. Caso contrário, uma XmlSchemaException é lançada.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) método


Adiciona todos os esquemas [Schema](../../) da linguagem de definição XML (XSD) no [XmlSchemaSet](../) dado ao [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | O objeto [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) método


Adiciona o [XmlSchema](../../xmlschema/) fornecido ao [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | O objeto [XmlSchema](../../xmlschema/) a ser adicionado ao [XmlSchemaSet](../). |

### Valor de retorno

Um objeto [XmlSchema](../../xmlschema/) se o esquema for válido. Se o esquema não for válido e um ValidationEventHandler for especificado, então **nullptr** é retornado e o evento de validação apropriado é disparado. Caso contrário, uma XmlSchemaException é lançada.

## Veja Também

* Definição de tipo [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaSet](../)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Espaço de nomes [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)