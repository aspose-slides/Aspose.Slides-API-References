---
title: get_LocalName()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el nombre local del nodo actual.
type: docs
weight: 27
url: /es/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() método

Devuelve el nombre local del nodo actual.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### Valor devuelto

El nombre del nodo actual sin el prefijo. Por ejemplo, **LocalName** es **book** para el elemento **<bk:book>**. Para los tipos de nodo que no tienen un nombre (como **[Text](../../../system.text/)**, **Comment**, y así sucesivamente), este método devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNodeReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)