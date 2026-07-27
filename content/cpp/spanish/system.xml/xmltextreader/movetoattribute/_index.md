---
title: MoveToAttribute()
second_title: Aspose.Slides para la referencia de API de C++
description: Se mueve al atributo con el nombre especificado.
type: docs
weight: 508
url: /es/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) método


Se mueve al atributo con el nombre especificado.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del atributo. |

### Valor devuelto

**true** si se encuentra el atributo; de lo contrario, **false**. Si **false**, la posición del lector no cambia.

## XmlTextReader::MoveToAttribute(String, String) método


Se mueve al atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor devuelto

**true** si se encuentra el atributo; de lo contrario, **false**. Si **false**, la posición del lector no cambia.

## XmlTextReader::MoveToAttribute(int32_t) método


Se mueve al atributo con el índice especificado.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | **int32_t** | El índice del atributo. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlTextReader](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)