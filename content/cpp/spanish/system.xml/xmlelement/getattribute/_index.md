---
title: GetAttribute()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el valor del atributo con el nombre especificado.
type: docs
weight: 209
url: /es/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) method

Devuelve el valor del atributo con el nombre especificado.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre del atributo a recuperar. Este es un nombre calificado. Se compara con el valor **get_Name** del nodo coincidente. |

### Valor de retorno

El valor del atributo especificado. Se devuelve una cadena vacía si no se encuentra un atributo coincidente o si el atributo no tiene un valor especificado o predeterminado.

## XmlElement::GetAttribute(String, String) method

Devuelve el valor del atributo con el nombre local y el URI de espacio de nombres especificados.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo a recuperar. |
| namespaceURI | [String](../../../system/string/) | El URI de espacio de nombres del atributo a recuperar. |

### Valor de retorno

El valor del atributo especificado. Se devuelve una cadena vacía si no se encuentra un atributo coincidente o si el atributo no tiene un valor especificado o predeterminado.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlElement](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)