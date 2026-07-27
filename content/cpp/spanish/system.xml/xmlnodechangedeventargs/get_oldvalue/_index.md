---
title: get_OldValue()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el valor original del nodo.
type: docs
weight: 53
url: /es/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() método


Devuelve el valor original del nodo.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Valor devuelto

El valor original del nodo. Este método devuelve **nullptr** si el nodo no es ni un atributo ni un nodo de texto, o si el nodo está siendo insertado. Si se llama en un evento **XmlDocument::NodeChanging**, **get_OldValue** devuelve el valor actual del nodo que será reemplazado si el cambio tiene éxito. Si se llama en un evento **XmlDocument::NodeChanged**, **get_OldValue** devuelve el valor del nodo antes del cambio.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNodeChangedEventArgs](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)