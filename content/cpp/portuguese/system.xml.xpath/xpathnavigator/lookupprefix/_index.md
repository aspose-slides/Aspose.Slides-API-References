---
title: LookupPrefix()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o prefixo declarado para o URI de namespace especificado.
type: docs
weight: 417
url: /pt/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) método

Retorna o prefixo declarado para o URI de namespace especificado.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | O URI de namespace a ser resolvido para o prefixo. |

### Valor de retorno

Um [String](../../../system/string/) que contém o prefixo de namespace atribuído ao URI de namespace especificado; caso contrário, [String::Empty](../../../system/string/empty/) se nenhum prefixo for atribuído ao URI de namespace especificado. O [String](../../../system/string/) retornado é atomizado.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Espaço de nomes [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)