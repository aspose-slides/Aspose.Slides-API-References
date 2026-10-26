---
title: LookupNamespace()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o URI do namespace para o prefixo especificado.
type: docs
weight: 118
url: /pt/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) método

Retorna o URI do namespace para o prefixo especificado.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo cujo URI do namespace você deseja resolver. Para corresponder ao namespace padrão, passe [String::Empty](../../../system/string/empty/). |

### Valor de Retorno

O URI do namespace para **prefix** ou **nullptr** se não houver namespace mapeado. A string retornada é atomizada. Para obter mais informações sobre strings atomizadas, veja a classe [XmlNameTable](../../xmlnametable/).

## Ver Também

* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)