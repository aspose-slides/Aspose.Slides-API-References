---
title: GetAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor do atributo com o nome local e o URI do namespace especificados.
type: docs
weight: 482
url: /pt/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) method


Retorna o valor do atributo com o nome local e o URI do namespace especificados.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo. **localName** diferencia maiúsculas de minúsculas. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

Um [String](../../../system/string/) que contém o valor do atributo especificado; [String::Empty](../../../system/string/empty/) se um atributo correspondente não for encontrado, ou se o [XPathNavigator](../) não estiver posicionado em um nó de elemento.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)