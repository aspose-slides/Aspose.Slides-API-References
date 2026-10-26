---
title: Contains()
second_title: Referência da API Aspose.Slides para C++
description: Indica se um esquema de linguagem de definição XML Schema (XSD) com o namespace de destino especificado está no XmlSchemaSet.
type: docs
weight: 196
url: /pt/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) método


Indica se um esquema de linguagem de definição XML [Schema](../../) (XSD) com o namespace de destino especificado está no [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | A propriedade **targetNamespace** do esquema. |

### Valor de Retorno

**true** se um esquema com o namespace de destino especificado estiver no [XmlSchemaSet](../); caso contrário, **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) método


Indica se o objeto [Schema](../../) de linguagem de definição XML (XSD) [XmlSchema](../../xmlschema/) especificado está no [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | O objeto [XmlSchema](../../xmlschema/). |

### Valor de Retorno

**true** se o objeto [XmlSchema](../../xmlschema/) estiver no [XmlSchemaSet](../); caso contrário, **false**.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaSet](../)
* Classe [XmlSchema](../../xmlschema/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)