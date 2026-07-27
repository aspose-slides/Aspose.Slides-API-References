---
title: get_LocalName()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, obtiene el nombre local del nodo actual.
type: docs
weight: 40
url: /es/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() método

Cuando se sobrescribe en una clase derivada, obtiene el nombre local del nodo actual.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### Valor de retorno

El nombre del nodo actual con el prefijo eliminado. Por ejemplo, **LocalName** es **book** para el elemento **<bk:book>**. Para los tipos de nodo que no tienen un nombre (como **[Text](../../../system.text/)**, **Comment**, y así sucesivamente), este método devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)