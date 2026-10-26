---
title: WriteAllText()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo archivo de texto o sobrescribe el existente y escribe el contenido de la cadena especificada en él usando la codificación especificada.
type: docs
weight: 469
url: /es/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) método

Crea un nuevo archivo de texto o sobrescribe el existente y escribe el contenido de la cadena especificada en él usando la codificación especificada.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | El archivo a crear o sobrescribir |
| contents | const [String](../../../system/string/)\& | Una matriz de cadenas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación de caracteres a usar |

## Ver también

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)