---
title: WriteSurrogateCharEntity()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos.
type: docs
weight: 261
url: /es/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) método

Cuando se sobrescribe en una clase derivada, genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lowChar | char16_t | El sustituto bajo. Este debe ser un valor entre 0xDC00 y 0xDFFF. |
| highChar | char16_t | El sustituto alto. Este debe ser un valor entre 0xD800 y 0xDBFF. |

## Ver también

* Clase [XmlWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)