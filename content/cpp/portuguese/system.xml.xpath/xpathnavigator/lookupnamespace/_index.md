---
title: LookupNamespace()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o URI do namespace para o prefixo especificado.
type: docs
weight: 404
url: /pt/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) method

Retorna o URI do namespace para o prefixo especificado.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo cujo URI do namespace você deseja resolver. Para corresponder ao namespace padrão, passe [String::Empty](../../../system/string/empty/). |

### Return Value

Um [String](../../../system/string/) que contém o URI do namespace atribuído ao prefixo de namespace especificado; **nullptr** se nenhum URI de namespace for atribuído ao prefixo especificado. O [String](../../../system/string/) retornado está atomizado.

## See Also

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)