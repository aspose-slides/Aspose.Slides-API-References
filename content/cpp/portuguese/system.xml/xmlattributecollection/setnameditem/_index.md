---
title: SetNamedItem()
second_title: Referência da API Aspose.Slides para C++
description: "Adiciona um XmlNode usando o resultado de XmlNode::get_Name."
type: docs
weight: 14
url: /pt/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) method

Adiciona um [XmlNode](../../xmlnode/) usando o resultado [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Um nó de atributo a ser armazenado nesta coleção. O nó poderá ser acessado posteriormente usando o nome do nó. Se um nó com esse nome já estiver presente na coleção, ele será substituído pelo novo; caso contrário, o nó será acrescentado ao final da coleção. |

### Valor de Retorno

Se o **node** substituir um nó existente com o mesmo nome, o nó antigo será retornado; caso contrário, o nó adicionado será retornado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)