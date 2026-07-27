---
title: Item()
second_title: Referência da API Aspose.Slides for C++
description: Recupera o nó no índice especificado em XmlNamedNodeMap.
type: docs
weight: 53
url: /pt/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) método


Recupera o nó no índice especificado em [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | A posição do índice do nó a ser recuperado de [XmlNamedNodeMap](../). O índice começa em zero; portanto, o índice do primeiro nó é 0 e o índice do último nó é [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Valor de Retorno

O [XmlNode](../../xmlnode/) no índice especificado. Se **index** for menor que 0 ou maior ou igual ao valor [XmlNamedNodeMap::get_Count](../get_count/), **nullptr** será retornado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)