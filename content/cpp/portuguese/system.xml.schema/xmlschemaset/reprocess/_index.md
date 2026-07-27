---
title: Reprocess()
second_title: Referência da API Aspose.Slides para C++
description: Reprocessa um esquema de linguagem de definição de XML Schema (XSD) que já existe no XmlSchemaSet.
type: docs
weight: 222
url: /pt/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) método

Reprocessa um esquema de linguagem de definição XML [Schema](../../) (XSD) que já existe no [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | O esquema a ser reprocessado. |

### Valor de Retorno

Um objeto [XmlSchema](../../xmlschema/) se o esquema for um esquema válido. Se o esquema não for válido e um ValidationEventHandler for especificado, **nullptr** é retornado e o evento de validação apropriado é disparado. Caso contrário, uma XmlSchemaException é lançada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaSet](../)
* namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)