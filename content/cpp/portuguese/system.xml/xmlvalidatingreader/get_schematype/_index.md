---
title: get_SchemaType()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um objeto do tipo de esquema.
type: docs
weight: 287
url: /pt/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() método

Retorna um objeto do tipo de esquema.

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```

### Valor de Retorno

XmlSchemaDatatype, XmlSchemaSimpleType ou XmlSchemaComplexType dependendo se o valor do nó é um tipo interno da linguagem de definição XML [Schema](../../../system.xml.schema/) (XSD) ou um simpleType ou complexType definido pelo usuário; **nullptr** se o nó atual não possui tipo de esquema.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)