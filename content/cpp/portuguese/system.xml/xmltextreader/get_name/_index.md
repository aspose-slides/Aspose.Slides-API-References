---
title: get_Name()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o nome qualificado do nó atual.
type: docs
weight: 14
url: /pt/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() método


Retorna o nome qualificado do nó atual.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### Valor de Retorno

O nome qualificado do nó atual. Por exemplo, **Name** é **bk:book** para o elemento **<bk:book>**.

## Observações



O nome retornado depende do valor [XmlTextReader::get_NodeType](../get_nodetype/) do nó. Os tipos de nó a seguir retornam os valores listados. Todos os outros tipos de nó retornam uma string vazia. 

| Tipo de Nó | Nome |
| --- | --- |
| [Attribute](../../../system/attribute/)| O nome do atributo. |
| DocumentType| O nome do tipo de documento. |
| Element| O nome da tag. |
| EntityReference| O nome da entidade referenciada. |
| ProcessingInstruction| O destino da instrução de processamento. |
| [XmlDeclaration](../../xmldeclaration/)| A string literal `xml`. |


## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)