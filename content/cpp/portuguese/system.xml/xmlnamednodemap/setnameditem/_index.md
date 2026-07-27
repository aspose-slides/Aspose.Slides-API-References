---
title: SetNamedItem()
second_title: Referência da API Aspose.Slides para C++
description: "Adiciona um XmlNode usando seu valor XmlNode::get_Name."
type: docs
weight: 27
url: /pt/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) método


Adiciona um [XmlNode](../../xmlnode/) usando o valor [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Um [XmlNode](../../xmlnode/) para armazenar no [XmlNamedNodeMap](../). Se um nó com esse nome já estiver presente no mapa, ele será substituído pelo novo. |

### Valor de Retorno

Se o **node** substituir um nó existente com o mesmo nome, o nó antigo será retornado; caso contrário, **nullptr** será retornado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)