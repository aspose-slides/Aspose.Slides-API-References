---
title: CompareDocument()
second_title: Aspose.Slides para C++ Referência da API
description: Quando substituído em uma classe derivada, compara os Identificadores Uniformes de Recursos (URIs) base de dois documentos com base na ordem em que os documentos foram carregados pelo processador XSLT (ou seja, a classe XslTransform).
type: docs
weight: 53
url: /pt/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) método

When overridden in a derived class, compares the base Uniform Resource Identifiers (URIs) of two documents based upon the order the documents were loaded by the XSLT processor (that is, the [XslTransform](../../xsltransform/) class).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | O URI base do primeiro documento a ser comparado. |
| nextbaseUri | [String](../../../system/string/) | O URI base do segundo documento a ser comparado. |

### Valor de Retorno

Um valor inteiro que descreve a ordem relativa dos dois URIs base: -1 se **baseUri** ocorrer antes de **nextbaseUri**; 0 se os dois URIs base forem idênticos; e 1 se **baseUri** ocorrer depois de **nextbaseUri**.

## Veja também

* Classe [String](../../../system/string/)
* Classe [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)