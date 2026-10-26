---
title: Item()
second_title: Referência da API Aspose.Slides para C++
description: Recupera um nó no índice especificado.
type: docs
weight: 14
url: /pt/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) método

Recupera um nó no índice especificado.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero na lista de nós. |

### Valor de retorno

O [XmlNode](../../xmlnode/) com o índice especificado na coleção. Se **index** for maior ou igual ao número de nós na lista, isso retorna **nullptr**.

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNodeList](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)