---
title: CreateAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nodo de atributo en el nodo de elemento actual utilizando el prefijo de espacio de nombres, el nombre local y el URI de espacio de nombres especificados con el valor indicado.
type: docs
weight: 1041
url: /es/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) método


Crea un nodo de atributo en el nodo de elemento actual utilizando el prefijo de espacio de nombres, el nombre local y el URI de espacio de nombres especificados con el valor indicado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | El prefijo de espacio de nombres del nuevo nodo de atributo (si lo hay). |
| localName | [String](../../../system/string/) | El nombre local del nuevo nodo de atributo que no puede [String::Empty](../../../system/string/empty/) o **nullptr**. |
| namespaceURI | [String](../../../system/string/) | El URI de espacio de nombres para el nuevo nodo de atributo (si lo hay). |
| value | [String](../../../system/string/) | El valor del nuevo nodo de atributo. Si se pasa [String::Empty](../../../system/string/empty/) o **nullptr**, se crea un nodo de atributo vacío. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)