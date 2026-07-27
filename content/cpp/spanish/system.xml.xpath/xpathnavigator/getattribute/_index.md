---
title: GetAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados.
type: docs
weight: 482
url: /es/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) método

Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo. **localName** distingue entre mayúsculas y minúsculas. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor de retorno

Un [String](../../../system/string/) que contiene el valor del atributo especificado; [String::Empty](../../../system/string/empty/) si no se encuentra un atributo coincidente, o si el [XPathNavigator](../) no está posicionado en un nodo de elemento.

## Véase también

* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)