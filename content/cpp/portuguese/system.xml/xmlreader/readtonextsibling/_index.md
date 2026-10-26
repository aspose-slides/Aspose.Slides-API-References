---
title: ReadToNextSibling()
second_title: Aspose.Slides para C++ Referência de API
description: Avança o XmlReader para o próximo elemento irmão com o nome qualificado especificado.
type: docs
weight: 924
url: /pt/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) método

Avança o [XmlReader](../) para o próximo elemento irmão com o nome qualificado especificado.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do elemento irmão para o qual você deseja mover. |

### Valor de Retorno

**true** se um elemento irmão correspondente for encontrado; caso contrário **false**. Se um elemento irmão correspondente não for encontrado, o [XmlReader](../) é posicionado na tag de fechamento (o valor [XmlReader::get_NodeType](../get_nodetype/) é [XmlNodeType::EndElement](../../xmlnodetype/)) do elemento pai.

## XmlReader::ReadToNextSibling(String, String) método

Avança o [XmlReader](../) para o próximo elemento irmão com o nome local e a URI de namespace especificados.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do elemento irmão para o qual você deseja mover. |
| namespaceURI | [String](../../../system/string/) | A URI de namespace do elemento irmão para o qual você deseja mover. |

### Valor de Retorno

**true** se um elemento irmão correspondente for encontrado; caso contrário **false**. Se um elemento irmão correspondente não for encontrado, o [XmlReader](../) é posicionado na tag de fechamento (o valor [XmlReader::get_NodeType](../get_nodetype/) é [XmlNodeType::EndElement](../../xmlnodetype/)) do elemento pai.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)