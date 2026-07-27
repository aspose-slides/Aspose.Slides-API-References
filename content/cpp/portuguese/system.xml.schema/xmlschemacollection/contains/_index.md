---
title: Contains()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um valor indicando se o targetNamespace do XmlSchema especificado está na coleção.
type: docs
weight: 66
url: /pt/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Retorna um valor indicando se o **targetNamespace** do [XmlSchema](../../xmlschema/) especificado está na coleção.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | O objeto [XmlSchema](../../xmlschema/). |

### Valor de Retorno

**true** se houver um esquema na coleção com o mesmo **targetNamespace**; caso contrário, **false**.

## XmlSchemaCollection::Contains(const String\&) method


Retorna um valor indicando se um esquema com o namespace especificado está na coleção.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | O URI do namespace associado ao esquema. Para XML Schemas, isso normalmente será o namespace de destino. |

### Valor de Retorno

**true** se um esquema com o namespace especificado estiver na coleção; caso contrário, **false**.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaCollection](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)