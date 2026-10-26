---
title: ReadAllLines()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee el contenido del archivo de texto especificado línea por línea a un arreglo de cadenas utilizando la codificación de caracteres especificada.
type: docs
weight: 300
url: /es/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) método

Lee el contenido del archivo de texto especificado línea por línea a un arreglo de cadenas utilizando la codificación de caracteres especificada.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo a leer |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación de caracteres a usar |

### Valor de retorno

Una matriz de cadenas donde cada elemento representa una línea única del archivo especificado

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Clase [String](../../../system/string/)
* Clase [File](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)