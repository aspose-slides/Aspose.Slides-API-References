---
title: WriteSurrogateCharEntity()
second_title: Referencia de API de Aspose.Slides para C++
description: Genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos.
type: docs
weight: 391
url: /es/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) método


Genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lowChar | char16_t | El sustituto bajo. Debe ser un valor entre **0xDC00** y **0xDFFF**. |
| highChar | char16_t | El sustituto alto. Debe ser un valor entre **0xD800** y **0xDBFF**. |

## Ver también

* Clase [XmlTextWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)