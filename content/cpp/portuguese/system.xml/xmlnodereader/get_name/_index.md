---
title: get_Name()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o nome qualificado do nó atual.
type: docs
weight: 14
url: /pt/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() método

Retorna o nome qualificado do nó atual.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```

### Valor de retorno

O nome qualificado do nó atual. Por exemplo, **Name** é **bk:book** para o elemento **<bk:book>**.

## Observações

O nome retornado depende do valor [XmlNodeReader::get_NodeType](../get_nodetype/) do nó. Os tipos de nó a seguir retornam os valores listados. Todos os demais tipos de nó retornam uma string vazia. 

| Tipo de Nó | Nome |
| --- | --- |
| [Attribute](../../../system/attribute/)| O nome do atributo. |
| DocumentType| O nome do tipo de documento. |
| Element| O nome da tag. |
| EntityReference| O nome da entidade referenciada. |
| ProcessingInstruction| O alvo da instrução de processamento. |
| [XmlDeclaration](../../xmldeclaration/)| A cadeia literal `xml`. |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)