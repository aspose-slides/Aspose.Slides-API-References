---
title: ResolveFunction()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, resolve uma referência de função e retorna um IXsltContextFunction que representa a função. O IXsltContextFunction é usado no tempo de execução para obter o valor de retorno da função.
type: docs
weight: 27
url: /pt/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) método


Quando sobrescrito em uma classe derivada, resolve uma referência de função e retorna um [IXsltContextFunction](../../ixsltcontextfunction/) que representa a função. O [IXsltContextFunction](../../ixsltcontextfunction/) é usado no tempo de execução para obter o valor de retorno da função.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | O prefixo da função conforme aparece na expressão [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | O nome da função. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Um array de tipos de argumento para a função que está sendo resolvida. Isso permite selecionar entre métodos com o mesmo nome (por exemplo, métodos sobrecarregados). |

### Valor de retorno

Um [IXsltContextFunction](../../ixsltcontextfunction/) que representa a função.

## Veja Também

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IXsltContextFunction](../../ixsltcontextfunction/)
* Classe [String](../../../system/string/)
* Classe [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)