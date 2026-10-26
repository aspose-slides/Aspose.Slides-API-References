---
title: SetAttribute()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece el valor del atributo con el nombre especificado.
type: docs
weight: 222
url: /es/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) método


Establece el valor del atributo con el nombre especificado.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre del atributo que se creará o modificará. Este es un nombre calificado. Si el nombre contiene dos puntos, se analiza en componentes de prefijo y nombre local. |
| value | [String](../../../system/string/) | El valor que se establecerá para el atributo. |

## XmlElement::SetAttribute(String, String, String) método


Establece el valor del atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |
| value | [String](../../../system/string/) | El valor que se establecerá para el atributo. |

### Valor de retorno

El valor del atributo.

## Véase también

* Clase [String](../../../system/string/)
* Clase [XmlElement](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)