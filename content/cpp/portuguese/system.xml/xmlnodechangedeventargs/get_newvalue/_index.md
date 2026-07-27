---
title: get_NewValue()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna o novo valor do nó.
type: docs
weight: 66
url: /pt/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() método

Retorna o novo valor do nó.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### Valor de Retorno

O novo valor do nó. Este método retorna **nullptr** se o nó não for um atributo nem um nó de texto, ou se o nó estiver sendo removido. Se chamado em um evento **XmlDocument::NodeChanging**, **get_NewValue** retorna o valor do nó se a alteração for bem-sucedida. Se chamado em um evento **XmlDocument::NodeChanged**, **get_NewValue** retorna o valor atual do nó.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)