---
title: InferSchema()
second_title: Referência da API Aspose.Slides para C++
description: Infere um esquema XML Schema Definition Language (XSD) a partir do documento XML contido no objeto XmlReader especificado.
type: docs
weight: 66
url: /pt/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method

Infere um esquema XML [Schema](../../) Linguagem de Definição (XSD) a partir do documento XML contido no objeto [XmlReader](../../../system.xml/xmlreader/) especificado.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Um objeto [XmlReader](../../../system.xml/xmlreader/) que contém o documento XML do qual inferir um esquema. |

### Valor de Retorno

Um objeto [XmlSchemaSet](../../xmlschemaset/) que contém os esquemas inferidos.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method

Infere um esquema XML [Schema](../../) Linguagem de Definição (XSD) a partir do documento XML contido no objeto [XmlReader](../../../system.xml/xmlreader/) especificado, e refina o esquema inferido usando um esquema existente no objeto [XmlSchemaSet](../../xmlschemaset/) especificado com o mesmo namespace de destino.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Um objeto [XmlReader](../../../system.xml/xmlreader/) que contém o documento XML do qual inferir um esquema. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Um objeto [XmlSchemaSet](../../xmlschemaset/) que contém um esquema existente usado para refinar o esquema inferido. |

### Valor de Retorno

Um objeto [XmlSchemaSet](../../xmlschemaset/) que contém os esquemas inferidos.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchemaSet](../../xmlschemaset/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)