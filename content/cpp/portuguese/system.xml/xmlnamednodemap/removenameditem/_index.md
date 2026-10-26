---
title: RemoveNamedItem()
second_title: Referência da API Aspose.Slides para C++
description: Remove o nó do XmlNamedNodeMap.
type: docs
weight: 40
url: /pt/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) método

Remove o nó de [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do nó a ser removido. O nome é comparado com o valor [XmlNode::get_Name](../../xmlnode/get_name/) do nó correspondente. |

### Valor de Retorno

O [XmlNode](../../xmlnode/) removido deste [XmlNamedNodeMap](../) ou **nullptr** se nenhum nó correspondente for encontrado.

## XmlNamedNodeMap::RemoveNamedItem(String, String) método

Remove um nó com os valores correspondentes de [XmlNode::get_LocalName](../../xmlnode/get_localname/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do nó a ser removido. |
| namespaceURI | [String](../../../system/string/) | O URI de namespace do nó a ser removido. |

### Valor de Retorno

O [XmlNode](../../xmlnode/) removido ou **nullptr** se nenhum nó correspondente for encontrado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [String](../../../system/string/)
* Classe [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)