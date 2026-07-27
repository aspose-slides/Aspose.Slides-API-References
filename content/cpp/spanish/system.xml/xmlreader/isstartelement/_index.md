---
title: IsStartElement()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Llama a XmlReader::MoveToContent y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío."
type: docs
weight: 885
url: /es/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() método


Llama a [XmlReader::MoveToContent](../movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### Valor de retorno

**true** si [XmlReader::MoveToContent](../movetocontent/) encuentra una etiqueta de inicio o una etiqueta de elemento vacío; **false** si se encontró un tipo de nodo distinto de [XmlNodeType::Element](../../xmlnodetype/).

## XmlReader::IsStartElement(String) método


Llama a [XmlReader::MoveToContent](../movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío y si el valor [XmlReader::get_Name](../get_name/) del elemento encontrado coincide con el argumento proporcionado.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | La cadena comparada con el valor **Name** del elemento encontrado. |

### Valor de retorno

**true** si el nodo resultante es un elemento y el valor **Name** coincide con la cadena especificada. **false** si se encontró un tipo de nodo distinto de [XmlNodeType::Element](../../xmlnodetype/) o si el valor **Name** del elemento no coincide con la cadena especificada.

## XmlReader::IsStartElement(String, String) método


Llama a [XmlReader::MoveToContent](../movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío y si los valores [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/) del elemento encontrado coinciden con las cadenas proporcionadas.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localname | [String](../../../system/string/) | La cadena a comparar con el valor **LocalName** del elemento encontrado. |
| ns | [String](../../../system/string/) | La cadena a comparar con el valor **NamespaceURI** del elemento encontrado. |

### Valor de retorno

**true** si el nodo resultante es un elemento. **false** si se encontró un tipo de nodo distinto de [XmlNodeType::Element](../../xmlnodetype/) o si los valores **LocalName** y **NamespaceURI** del elemento no coinciden con las cadenas especificadas.

## Ver también

* Clase [XmlReader](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)