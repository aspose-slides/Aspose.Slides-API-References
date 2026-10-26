---
title: Compile()
second_title: Referencia de API de Aspose.Slides para C++
description: Compila la expresión XPath especificada y devuelve un objeto XPathExpression que representa la expresión XPath.
type: docs
weight: 66
url: /es/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) método

Compila la expresión [XPath](../../) especificada y devuelve un objeto [XPathExpression](../) que representa la expresión [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Una expresión [XPath](../../). |

### Valor devuelto

Un objeto [XPathExpression](../).

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) método

Compila la expresión [XPath](../../) especificada, con el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para la resolución de espacios de nombres, y devuelve un objeto [XPathExpression](../) que representa la expresión [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Una expresión [XPath](../../). |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Un objeto que implementa la interfaz [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) para la resolución de espacios de nombres. |

### Valor devuelto

Un objeto [XPathExpression](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XPathExpression](../)
* Clase [String](../../../system/string/)
* Clase [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)