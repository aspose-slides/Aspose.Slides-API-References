---
title: AppendAllText()
second_title: Referencia de API de Aspose.Slides para C++
description: Añade la cadena especificada al archivo especificado usando la codificación especificada.
type: docs
weight: 14
url: /es/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) método

Agrega la cadena especificada al archivo especificado usando la codificación especificada.

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo al que se añadirá la cadena |
| contents | const [String](../../../system/string/)\& | La cadena a escribir en el archivo |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación de caracteres a usar |

## Ver también

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Clase [String](../../../system/string/)
* Clase [File](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)