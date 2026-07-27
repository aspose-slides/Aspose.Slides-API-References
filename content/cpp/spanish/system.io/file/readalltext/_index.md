---
title: ReadAllText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee el contenido del archivo de texto especificado en un único objeto String usando la codificación de caracteres especificada.
type: docs
weight: 313
url: /es/system.io/file/readalltext/
---
## File::ReadAllText(const String&, const EncodingPtr&) método

Lee el contenido del archivo de texto especificado a un único objeto [String](../../../system/string/) usando la codificación de caracteres especificada.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | La ruta del archivo a leer |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | La codificación de caracteres a usar |

### Valor devuelto

Una string que contiene el contenido del archivo especificado

## Ver también

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Clase [String](../../../system/string/)
* Clase [File](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)