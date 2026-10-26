---
title: get_NewValue()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el nuevo valor del nodo.
type: docs
weight: 66
url: /es/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() método

Devuelve el nuevo valor del nodo.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### Valor devuelto

El nuevo valor del nodo. Este método devuelve **nullptr** si el nodo no es ni un atributo ni un nodo de texto, o si el nodo está siendo eliminado. Si se llama en un evento **XmlDocument::NodeChanging**, **get_NewValue** devuelve el valor del nodo si el cambio es exitoso. Si se llama en un evento **XmlDocument::NodeChanged**, **get_NewValue** devuelve el valor actual del nodo.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNodeChangedEventArgs](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)