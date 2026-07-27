---
title: Matches()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o nó atual corresponde à XPathExpression especificada.
type: docs
weight: 820
url: /pt/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) método


Determina se o nó atual corresponde ao [XPathExpression](../../xpathexpression/) especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Um objeto [XPathExpression](../../xpathexpression/) contendo a expressão [XPath](../../) compilada. |

### Valor de Retorno

**true** se o nó atual corresponde ao [XPathExpression](../../xpathexpression/); caso contrário, **false**.

## XPathNavigator::Matches(String) método


Determina se o nó atual corresponde à expressão [XPath](../../) especificada.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A expressão [XPath](../../). |

### Valor de Retorno

**true** se o nó atual corresponde à expressão [XPath](../../) especificada; caso contrário, **false**.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathExpression](../../xpathexpression/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)