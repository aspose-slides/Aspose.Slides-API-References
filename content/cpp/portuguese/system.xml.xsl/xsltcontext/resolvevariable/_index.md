---
title: ResolveVariable()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, resolve uma referência de variável e retorna um IXsltContextVariable que representa a variável.
type: docs
weight: 14
url: /pt/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) método

Quando sobrescrito em uma classe derivada, resolve uma referência de variável e retorna um [IXsltContextVariable](../../ixsltcontextvariable/) que representa a variável.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | O prefixo da variável como aparece na expressão [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | O nome da variável. |

### Valor de Retorno

Um [IXsltContextVariable](../../ixsltcontextvariable/) que representa a variável em tempo de execução.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IXsltContextVariable](../../ixsltcontextvariable/)
* Classe [String](../../../system/string/)
* Classe [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)