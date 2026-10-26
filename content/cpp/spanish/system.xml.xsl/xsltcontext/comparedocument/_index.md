---
title: CompareDocument()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, compara los Identificadores Uniformes de Recursos (URIs) base de dos documentos según el orden en que los documentos fueron cargados por el procesador XSLT (es decir, la clase XslTransform).
type: docs
weight: 53
url: /es/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) método


Cuando se sobrescribe en una clase derivada, compara los Identificadores Uniformes de Recursos (URIs) base de dos documentos según el orden en que los documentos fueron cargados por el procesador XSLT (es decir, la clase [XslTransform](../../xsltransform/)).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | El URI base del primer documento a comparar. |
| nextbaseUri | [String](../../../system/string/) | El URI base del segundo documento a comparar. |

### Valor de retorno

Un valor entero que describe el orden relativo de los dos URI base: -1 si **baseUri** ocurre antes que **nextbaseUri**; 0 si los dos URI base son idénticos; y 1 si **baseUri** ocurre después de **nextbaseUri**.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XsltContext](../)
* Espacio de nombres [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)