---
title: PreserveWhitespace()
second_title: Aspose.Slides para C++ Referência da API
description: Quando sobrescrito em uma classe derivada, avalia se deve preservar os nós de espaço em branco ou removê-los no contexto fornecido.
type: docs
weight: 40
url: /pt/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) método

Quando substituído em uma classe derivada, avalia se deve preservar os nós de espaço em branco ou removê-los no contexto fornecido.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | O nó de espaço em branco que deve ser preservado ou removido no contexto atual. |

### Valor de Retorno

**true** se o espaço em branco deve ser preservado; **false** se o espaço em branco deve ser removido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Classe [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)