---
title: NewLineHandling
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica cómo manejar los saltos de línea.
type: docs
weight: 690
url: /es/system.xml/newlinehandling/
---
## NewLineHandling enum

Especifica cómo manejar los saltos de línea.

```cpp
enum class NewLineHandling
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Replace | 0 | Los caracteres de nueva línea se reemplazan para coincidir con el carácter especificado en el valor [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | Los caracteres de nueva línea se convierten en entidades. Esta configuración preserva todos los caracteres cuando la salida es leída por un [XmlReader](../xmlreader/) normalizador. |
| None | 2 | Los caracteres de nueva línea no se modifican. La salida es la misma que la entrada. |

## Ver también

* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)