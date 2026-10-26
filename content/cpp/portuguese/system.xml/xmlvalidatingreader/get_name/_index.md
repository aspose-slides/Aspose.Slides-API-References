---
title: get_Name()
second_title: Referência de API do Aspose.Slides para C++
description: Retorna o nome qualificado do nó atual.
type: docs
weight: 14
url: /pt/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() método

Retorna o nome qualificado do nó atual.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### Valor de Retorno

O nome qualificado do nó atual. Por exemplo, **Name** é **bk:book** para o elemento **<bk:book>**.

## Observações

O nome retornado depende do XmlValidatingReader::NodeType do nó. Os seguintes tipos de nó retornam os valores listados. Todos os outros tipos de nó retornam uma string vazia.

| Node Type | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| O nome do atributo. |
| DocumentType| O nome do tipo de documento. |
| Element| O nome da tag. |
| EntityReference| O nome da entidade referenciada. |
| ProcessingInstruction| O destino da instrução de processamento. |
| [XmlDeclaration](../../xmldeclaration/)| A string literal `xml`. |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)