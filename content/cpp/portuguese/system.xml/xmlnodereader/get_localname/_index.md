---
title: get_LocalName()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o nome local do nó atual.
type: docs
weight: 27
url: /pt/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() método


Retorna o nome local do nó atual.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```


### Valor de Retorno

O nome do nó atual com o prefixo removido. Por exemplo, **LocalName** é **book** para o elemento **<bk:book>**. Para tipos de nó que não possuem nome (como **[Text](../../../system.text/)**, **Comment**, e assim por diante), este método retorna [String::Empty](../../../system/string/empty/).

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)