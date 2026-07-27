---
title: ReadAttributeValue()
second_title: Aspose.Slides para C++ Referência da API
description: Analisa o valor do atributo em um ou mais nós Text, EntityReference ou EndEntity.
type: docs
weight: 508
url: /pt/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() método

Analisa o valor do atributo em um ou mais nós **[Text](../../../system.text/)**, **EntityReference** ou **EndEntity**.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### Valor de Retorno

**true** se houver nós para retornar. **false** se o leitor não estiver posicionado em um nó de atributo quando a chamada inicial for feita ou se todos os valores de atributo já foram lidos. Um atributo vazio, como **misc=\"\"**, retorna **true** com um único nó com um valor de [String::Empty](../../../system/string/empty/).

## Ver Também

* Classe [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)