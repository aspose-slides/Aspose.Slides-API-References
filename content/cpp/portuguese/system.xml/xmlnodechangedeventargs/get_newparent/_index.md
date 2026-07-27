---
title: get_NewParent()
second_title: Referência da API Aspose.Slides for C++
description: "Retorna o valor de XmlNode::get_ParentNode após a operação ser concluída."
type: docs
weight: 40
url: /pt/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() método


Retorna o valor de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) após a operação ser concluída.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### Valor de retorno

O valor de **ParentNode** após a operação ser concluída. Este método retorna **nullptr** se o nó estiver sendo removido. Para nós de atributo, este método retorna o valor [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNodeChangedEventArgs](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)