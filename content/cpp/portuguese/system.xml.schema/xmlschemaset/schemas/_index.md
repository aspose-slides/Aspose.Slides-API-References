---
title: Schemas()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma coleção de todos os esquemas da linguagem de definição XML Schema (XSD) no XmlSchemaSet.
type: docs
weight: 248
url: /pt/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() método


Retorna uma coleção de todos os esquemas de definição de linguagem XML (XSD) [Schema](../../) no [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### Valor de Retorno

Um objeto IList contendo todos os esquemas que foram adicionados ao [XmlSchemaSet](../). Se nenhum esquema foi adicionado ao [XmlSchemaSet](../), uma coleção vazia é retornada.

## XmlSchemaSet::Schemas(String) método


Retorna uma coleção de todos os esquemas de definição de linguagem XML (XSD) [Schema](../../) no [XmlSchemaSet](../) que pertencem ao espaço de nomes fornecido.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | A propriedade **targetNamespace** do esquema. |

### Valor de Retorno

Um objeto IList contendo todos os esquemas que foram adicionados ao [XmlSchemaSet](../) e que pertencem ao espaço de nomes fornecido. Se nenhum esquema foi adicionado ao [XmlSchemaSet](../), uma coleção vazia é retornada.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IList](../../../system.collections.generic/ilist/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaSet](../)
* Classe [List](../../../system.collections.generic/list/)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)