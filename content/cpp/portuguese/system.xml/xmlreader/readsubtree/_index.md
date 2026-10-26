---
title: ReadSubtree()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma nova instância de XmlReader que pode ser usada para ler o nó atual e todos os seus descendentes.
type: docs
weight: 963
url: /pt/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() método

Retorna uma nova instância de [XmlReader](../) que pode ser usada para ler o nó atual e todos os seus descendentes.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### Valor de Retorno

Uma nova instância de leitor XML definida para [ReadState::Initial](../../readstate/). Chamar o método [XmlReader::Read](../read/) posiciona o novo leitor no nó que era atual antes da chamada ao método [XmlReader::ReadSubtree](./).

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [XmlReader](../)
* namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)