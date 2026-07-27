---
title: MoveToAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: Se desplaza al atributo con el nombre especificado.
type: docs
weight: 456
url: /es/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) método

Se desplaza al atributo con el nombre especificado.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del atributo. |

### Valor devuelto

**true** si se encuentra el atributo; de lo contrario, **false**. Si **false**, la posición del lector no cambia.

## XmlValidatingReader::MoveToAttribute(String, String) método

Se desplaza al atributo con el nombre local y el Identificador Uniforme de Recursos (URI) del espacio de nombres especificados.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor devuelto

**true** si se encuentra el atributo; de lo contrario, **false**. Si **false**, la posición del lector no cambia.

## XmlValidatingReader::MoveToAttribute(int32_t) método

Se desplaza al atributo con el índice especificado.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | **int32_t** | El índice del atributo. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlValidatingReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)