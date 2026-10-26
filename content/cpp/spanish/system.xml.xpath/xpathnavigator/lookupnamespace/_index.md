---
title: LookupNamespace()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el URI del espacio de nombres para el prefijo especificado.
type: docs
weight: 404
url: /es/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) método

Devuelve el URI del espacio de nombres para el prefijo especificado.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo cuyo URI del espacio de nombres desea resolver. Para coincidir con el espacio de nombres predeterminado, pase [String::Empty](../../../system/string/empty/). |

### Valor devuelto

Un [String](../../../system/string/) que contiene el URI del espacio de nombres asignado al prefijo de espacio de nombres especificado; **nullptr** si no se asigna ningún URI de espacio de nombres al prefijo especificado. El [String](../../../system/string/) devuelto está atomizado.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)