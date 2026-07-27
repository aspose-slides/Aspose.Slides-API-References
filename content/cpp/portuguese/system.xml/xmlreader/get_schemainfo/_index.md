---
title: get_SchemaInfo()
second_title: Referência da API Aspose.Slides para C++
description: Retorna as informações de esquema que foram atribuídas ao nó atual como resultado da validação de esquema.
type: docs
weight: 196
url: /pt/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() método

Retorna as informações de esquema que foram atribuídas ao nó atual como resultado da validação de esquema.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### Valor de Retorno

Um objeto IXmlSchemaInfo contendo as informações de esquema para o nó atual. [Schema](../../../system.xml.schema/) informação pode ser definida em elementos, atributos ou em nós de texto com um valor [XmlReader::get_ValueType](../get_valuetype/) não nulo. Se o nó atual não for um dos tipos de nó acima, ou se a instância [XmlReader](../) não relatar informações de esquema, este método retorna **nullptr**. Se este método for chamado a partir de um objeto [XmlTextReader](../../xmltextreader/) ou [XmlValidatingReader](../../xmlvalidatingreader/), este método sempre retorna **nullptr**. Essas implementações [XmlReader](../) não expõem informações de esquema através do método get_SchemaInfo.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)