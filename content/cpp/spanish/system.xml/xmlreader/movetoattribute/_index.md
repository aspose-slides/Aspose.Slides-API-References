---
title: MoveToAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: "Cuando se sobrescribe en una clase derivada, se desplaza al atributo con el valor especificado de XmlReader::get_Name."
type: docs
weight: 625
url: /es/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) método

Cuando se sobrescribe en una clase derivada, se desplaza al atributo con el valor especificado de [XmlReader::get_Name](../get_name/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del atributo. |

### Valor devuelto

**true** si se encuentra el atributo; de lo contrario, **false**. Si **false**, la posición del lector no cambia.

## XmlReader::MoveToAttribute(String, String) método

Cuando se sobrescribe en una clase derivada, se desplaza al atributo con los valores especificados de [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre local del atributo. |
| ns | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor devuelto

**true** si se encuentra el atributo; de lo contrario, **false**. Si **false**, la posición del lector no cambia.

## XmlReader::MoveToAttribute(int32_t) método

Cuando se sobrescribe en una clase derivada, se desplaza al atributo con el índice especificado.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | **int32_t** | El índice del atributo. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)