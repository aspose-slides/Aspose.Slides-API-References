---
title: Compile()
second_title: Referência da API Aspose.Slides para C++
description: Compila a expressão XPath especificada e retorna um objeto XPathExpression que representa a expressão XPath.
type: docs
weight: 66
url: /pt/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) método


Compila a expressão [XPath](../../) especificada e retorna um objeto [XPathExpression](../) que representa a expressão [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Uma expressão [XPath](../../). |

### Valor de Retorno

Um objeto [XPathExpression](../).

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) método


Compila a expressão [XPath](../../) especificada, com o objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para a resolução de namespace, e retorna um objeto [XPathExpression](../) que representa a expressão [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Uma expressão [XPath](../../). |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Um objeto que implementa a interface [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) para a resolução de namespace. |

### Valor de Retorno

Um objeto [XPathExpression](../).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathExpression](../)
* Classe [String](../../../system/string/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Espaço de nomes [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)