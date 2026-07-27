---
title: LookupPrefix()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el prefijo declarado para el URI de espacio de nombres especificado.
type: docs
weight: 417
url: /es/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) método


Devuelve el prefijo declarado para el URI de espacio de nombres especificado.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | El URI de espacio de nombres a resolver para el prefijo. |

### Valor devuelto

Un [String](../../../system/string/) que contiene el prefijo de espacio de nombres asignado al URI de espacio de nombres especificado; de lo contrario, [String::Empty](../../../system/string/empty/) si no se asigna un prefijo al URI de espacio de nombres especificado. El [String](../../../system/string/) devuelto está atomizado.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)