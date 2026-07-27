---
title: ToString()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el valor de cadena del XmlQualifiedName.
type: docs
weight: 79
url: /es/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const método


Devuelve el valor de cadena del [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### Valor de retorno

El valor de cadena del [XmlQualifiedName](../) en el formato de **namespace:localname**. Si el objeto no tiene un espacio de nombres definido, este método devuelve solo el nombre local.

## XmlQualifiedName::ToString(const String\&, const String\&) método


Devuelve el valor de cadena del [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | El nombre del objeto. |
| ns | const [String](../../../system/string/)\& | El espacio de nombres del objeto. |

### Valor de retorno

El valor de cadena del [XmlQualifiedName](../) en el formato de **namespace:localname**. Si el objeto no tiene un espacio de nombres definido, este método devuelve solo el nombre local.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlQualifiedName](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)