---
title: get_LocalName()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el nombre local del nodo actual.
type: docs
weight: 27
url: /es/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() method


Devuelve el nombre local del nodo actual.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```


### Valor devuelto

El nombre del nodo actual sin el prefijo. Por ejemplo, **LocalName** es **book** para el elemento **<bk:book>**. Para los tipos de nodo que no tienen nombre (como **[Text](../../../system.text/)**, **Comment**, y así sucesivamente), este método devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlValidatingReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)