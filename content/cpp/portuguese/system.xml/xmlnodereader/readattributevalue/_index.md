---
title: ReadAttributeValue()
second_title: Referência da API Aspose.Slides para C++
description: Analisa o valor do atributo em um ou mais nós Text, EntityReference ou EndEntity.
type: docs
weight: 430
url: /pt/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() método

Analisa o valor do atributo em um ou mais nós **[Text](../../../system.text/)**, **EntityReference** ou **EndEntity**.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### Valor de Retorno

**true** se houver nós a serem retornados. **false** se o leitor não estiver posicionado em um nó de atributo quando a chamada inicial for feita ou se todos os valores de atributo já tiverem sido lidos. Um atributo vazio, como **misc=\"\"**, retorna **true** com um único nó com o valor de [String::Empty](../../../system/string/empty/).

## Veja Também

* Classe [XmlNodeReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)