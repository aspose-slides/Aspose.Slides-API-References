---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona o esquema localizado pelo URL fornecido à coleção de esquemas.
type: docs
weight: 40
url: /pt/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) method

Adiciona o esquema localizado pelo URL fornecido à coleção de esquemas.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | O URI do namespace associado ao esquema. Para XML Schemas, normalmente será o **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | O URL que especifica o esquema a ser carregado. |

### Valor de Retorno

O [XmlSchema](../../xmlschema/) adicionado à coleção de esquemas; **nullptr** se o esquema a ser adicionado for um esquema XDR ou se houver erros de compilação no esquema.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) method

Adiciona o esquema contido em [XmlReader](../../../system.xml/xmlreader/) à coleção de esquemas.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | O URI do namespace associado ao esquema. Para XML Schemas, normalmente será o **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) contendo o esquema a ser adicionado. |

### Valor de Retorno

O [XmlSchema](../../xmlschema/) adicionado à coleção de esquemas; **nullptr** se o esquema a ser adicionado for um esquema XDR ou se houver erros de compilação no esquema.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Adiciona o esquema contido em [XmlReader](../../../system.xml/xmlreader/) à coleção de esquemas. O [XmlResolver](../../../system.xml/xmlresolver/) especificado é usado para resolver quaisquer recursos externos.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | O URI do namespace associado ao esquema. Para XML Schemas, normalmente será o **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) contendo o esquema a ser adicionado. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver namespaces referenciados em elementos **include** e **import** ou no atributo **x-schema** (esquemas XDR). Se for **nullptr**, as referências externas não são resolvidas. |

### Valor de Retorno

O [XmlSchema](../../xmlschema/) adicionado à coleção de esquemas; **nullptr** se o esquema a ser adicionado for um esquema XDR ou se houver erros de compilação no esquema.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) method

Adiciona o [XmlSchema](../../xmlschema/) à coleção.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | O [XmlSchema](../../xmlschema/) a ser adicionado à coleção. |

### Valor de Retorno

O objeto [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Adiciona o [XmlSchema](../../xmlschema/) à coleção. O [XmlResolver](../../../system.xml/xmlresolver/) especificado é usado para resolver quaisquer referências externas.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | O [XmlSchema](../../xmlschema/) a ser adicionado à coleção. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver namespaces referenciados em elementos **include** e **import**. Se for **nullptr**, as referências externas não são resolvidas. |

### Valor de Retorno

O [XmlSchema](../../xmlschema/) adicionado à coleção de esquemas.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) method

Adiciona todos os namespaces definidos na coleção fornecida (incluindo seus esquemas associados) a esta coleção.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | O [XmlSchemaCollection](../) que você deseja adicionar a esta coleção. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)