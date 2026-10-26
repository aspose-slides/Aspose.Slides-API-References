---
title: OpenText()
second_title: Aspose.Slides para C++ Referencia de API
description: Abre el archivo existente especificado para leer texto usando codificación UTF-8 sin compartir.
type: docs
weight: 261
url: /es/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) método


Abre el archivo existente especificado para leer texto usando codificación UTF-8 sin compartir.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo a abrir |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación de caracteres a usar |

### Valor de retorno

Un puntero compartido a un objeto [StreamWriter](../../streamwriter/) asociado con el archivo abierto

## Ver también

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)