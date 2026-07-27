---
title: get_LocalName()
second_title: Referência da API Aspose.Slides for C++
description: Quando substituído em uma classe derivada, obtém o nome local do nó atual.
type: docs
weight: 40
url: /pt/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() método


Quando substituído em uma classe derivada, obtém o nome local do nó atual.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Valor de Retorno

O nome do nó atual com o prefixo removido. Por exemplo, **LocalName** é **book** para o elemento **<bk:book>**. Para tipos de nó que não têm nome (como **[Text](../../../system.text/)**, **Comment**, e assim por diante), este método retorna [String::Empty](../../../system/string/empty/).

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)