---
title: get_OldParent()
second_title: Referência da API Aspose.Slides para C++
description: "Retorna o valor de XmlNode::get_ParentNode antes da operação começar."
type: docs
weight: 27
url: /pt/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() método

Retorna o valor de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) antes da operação começar.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### Valor de Retorno

O valor do **ParentNode** antes da operação começar. Este método retorna **nullptr** se o nó não tinha um pai. Para nós de atributo, este método retorna o valor [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)