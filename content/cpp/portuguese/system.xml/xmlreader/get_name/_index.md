---
title: get_Name()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, obtém o nome qualificado do nó atual.
type: docs
weight: 27
url: /pt/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() método


Quando sobrescrito em uma classe derivada, obtém o nome qualificado do nó atual.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Valor de Retorno

O nome qualificado do nó atual. Por exemplo, **Name** é **bk:book** para o elemento **<bk:book>**.

## Observações



O nome retornado depende do valor [XmlReader::get_NodeType](../get_nodetype/) do nó. Os tipos de nó a seguir retornam os valores listados. Todos os demais tipos de nó retornam uma string vazia. 

| Tipo de Nó | Nome |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| O nome do atributo. |
| `DocumentType`| O nome do tipo de documento. |
| `Element`| O nome da tag. |
| `EntityReference`| O nome da entidade referenciada. |
| `ProcessingInstruction`| O destino da instrução de processamento. |
| [XmlDeclaration](../../xmldeclaration/)| A cadeia literal `xml`. |


## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)