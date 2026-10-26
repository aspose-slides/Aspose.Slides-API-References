---
title: ReadLines()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el contenido del archivo de texto especificado línea por línea usando la codificación de caracteres especificada y devuelve una colección enumerable de cadenas, cada una de las cuales representa una única línea del contenido del archivo.
type: docs
weight: 326
url: /es/system.io/file/readlines/
---
## File::ReadLines(const String&, const EncodingPtr&) método


Lee el contenido del archivo de texto especificado línea por línea usando la codificación de caracteres especificada y devuelve una colección enumerable de cadenas, cada una de las cuales representa una única línea del contenido del archivo.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo a leer |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación de caracteres a utilizar |

### Valor de retorno

Una colección enumerable de cadenas que representa el contenido del archivo especificado

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Clase [String](../../../system/string/)
* Clase [File](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)