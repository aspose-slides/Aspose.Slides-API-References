---
title: RemoveRecursive()
second_title: Aspose.Slides para C++ API de Referência
description: Remove o esquema de linguagem de definição XML Schema (XSD) especificado e todos os esquemas que ele importa do XmlSchemaSet.
type: docs
weight: 183
url: /pt/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) método


Remove o esquema [Schema](../../) XML de linguagem de definição (XSD) especificado e todos os esquemas que ele importa do [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | O objeto [XmlSchema](../../xmlschema/) a ser removido do [XmlSchemaSet](../). |

### Valor de Retorno

**true** se o objeto [XmlSchema](../../xmlschema/) e todas as suas importações foram removidos com sucesso; caso contrário, **false**.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)