---
title: get_OldValue()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor original do nó.
type: docs
weight: 53
url: /pt/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() method


Retorna o valor original do nó.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Valor de Retorno

O valor original do nó. Este método retorna **nullptr** se o nó não for nem um atributo nem um nó de texto, ou se o nó estiver sendo inserido. Se chamado em um evento **XmlDocument::NodeChanging**, **get_OldValue** retorna o valor atual do nó que será substituído se a alteração for bem-sucedida. Se chamado em um evento **XmlDocument::NodeChanged**, **get_OldValue** retorna o valor do nó antes da alteração.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)