---
title: ReadAttributeValue()
second_title: Referência da API Aspose.Slides para C++
description: Analisa o valor do atributo em um ou mais nós Text, EntityReference ou EndEntity.
type: docs
weight: 560
url: /pt/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() method

Analisa o valor do atributo em um ou mais nós **[Text](../../../system.text/)**, **EntityReference** ou **EndEntity**.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Valor de Retorno

**true** se houver nós para retornar. **false** se o leitor não estiver posicionado em um nó de atributo quando a chamada inicial for feita ou se todos os valores de atributo já foram lidos. Um atributo vazio, como **misc=\"\"**, retorna **true** com um único nó com um valor de [String::Empty](../../../system/string/empty/).

## Ver também

* Classe [XmlTextReader](../)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)