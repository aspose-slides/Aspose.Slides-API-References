---
title: MoveToAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: Se desplaza al atributo con el nombre especificado.
type: docs
weight: 300
url: /es/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) método


Se desplaza al atributo con el nombre especificado.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del atributo. |

### Valor devuelto

**true** si el atributo se encuentra; de lo contrario, **false**. Si **false**, la posición del lector no cambia.

## XmlNodeReader::MoveToAttribute(String, String) método


Se desplaza al atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor devuelto

**true** si el atributo se encuentra; de lo contrario, **false**. Si **false**, la posición del lector no cambia.

## XmlNodeReader::MoveToAttribute(int32_t) método


Se desplaza al atributo con el índice especificado.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attributeIndex | **int32_t** | El índice del atributo. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)