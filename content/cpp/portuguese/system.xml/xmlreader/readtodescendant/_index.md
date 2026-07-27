---
title: ReadToDescendant()
second_title: Referência da API Aspose.Slides para C++
description: Avança o XmlReader para o próximo elemento descendente com o nome qualificado especificado.
type: docs
weight: 911
url: /pt/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) método


Avança o [XmlReader](../) para o próximo elemento descendente com o nome qualificado especificado.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do elemento para o qual você deseja mover. |

### Valor de Retorno

**true** se um elemento descendente correspondente for encontrado; caso contrário, **false**. Se um elemento filho correspondente não for encontrado, o [XmlReader](../) é posicionado na tag de fechamento (o valor [XmlReader::get_NodeType](../get_nodetype/) é [XmlNodeType::EndElement](../../xmlnodetype/)) do elemento. Se o [XmlReader](../) não estiver posicionado em um elemento quando [XmlReader::ReadToDescendant(String)](./) for chamado, este método retorna **false** e a posição do [XmlReader](../) não é alterada.

## XmlReader::ReadToDescendant(String, String) método


Avança o [XmlReader](../) para o próximo elemento descendente com o nome local e o URI de namespace especificados.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do elemento para o qual você deseja mover. |
| namespaceURI | [String](../../../system/string/) | O URI de namespace do elemento para o qual você deseja mover. |

### Valor de Retorno

**true** se um elemento descendente correspondente for encontrado; caso contrário, **false**. Se um elemento filho correspondente não for encontrado, o [XmlReader](../) é posicionado na tag de fechamento (o valor [XmlReader::get_NodeType](../get_nodetype/) é [XmlNodeType::EndElement](../../xmlnodetype/)) do elemento. Se o [XmlReader](../) não estiver posicionado em um elemento quando [XmlReader::ReadToDescendant(String,String)](./) for chamado, este método retorna **false** e a posição do [XmlReader](../) não é alterada.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)