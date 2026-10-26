---
title: ReadAttributeValue()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, analisa o valor do atributo em um ou mais nós Text, EntityReference ou EndEntity.
type: docs
weight: 677
url: /pt/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() método

Quando sobrescrito em uma classe derivada, analisa o valor do atributo em um ou mais nós **[Text](../../../system.text/)**, **EntityReference** ou **EndEntity**.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### Valor de Retorno

**true** se houver nós a serem retornados. **false** se o leitor não estiver posicionado em um nó de atributo quando a chamada inicial for feita ou se todos os valores de atributo já foram lidos. Um atributo vazio, como **misc=""**, retorna **true** com um único nó com valor [String::Empty](../../../system/string/empty/).

## Veja Também

* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)