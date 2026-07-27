---
title: Invoke()
second_title: Referência da API Aspose.Slides para C++
description: Fornece o método para invocar a função com os argumentos fornecidos no contexto especificado.
type: docs
weight: 53
url: /pt/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) method

Fornece o método para invocar a função com os argumentos fornecidos no contexto especificado.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | O contexto XSLT para a chamada da função. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Os argumentos da chamada da função. Cada argumento é um elemento no array. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | O nó de contexto para a chamada da função. |

### Valor de Retorno

Um [Object](../../../system/object/) que representa o valor de retorno da função.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [XsltContext](../../xsltcontext/)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Classe [IXsltContextFunction](../)
* Espaço de nomes [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)