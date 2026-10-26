---
title: ReadElementContentAsObject()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el elemento actual y devuelve el contenido como un Object.
type: docs
weight: 469
url: /es/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() method


Lee el elemento actual y devuelve el contenido como un [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### Valor de retorno

Un objeto empaquetado del tipo más apropiado. El valor [XmlReader::get_ValueType](../get_valuetype/) determina el tipo apropiado. Si el contenido está tipado como un tipo de lista, este método devuelve una matriz de objetos empaquetados del tipo apropiado.

## XmlReader::ReadElementContentAsObject(String, String) método


Comprueba que el nombre local y el URI del espacio de nombres especificados coincidan con los del elemento actual, luego lee el elemento actual y devuelve el contenido como un [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del elemento. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del elemento. |

### Valor de retorno

Un objeto empaquetado del tipo más apropiado. El valor [XmlReader::get_ValueType](../get_valuetype/) determina el tipo apropiado. Si el contenido está tipado como un tipo de lista, este método devuelve una matriz de objetos empaquetados del tipo apropiado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)