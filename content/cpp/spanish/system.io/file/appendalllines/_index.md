---
title: AppendAllLines()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega cadenas de la colección de cadenas especificada al archivo especificado usando la codificación especificada, escribiendo cada cadena en una nueva línea. Si el archivo especificado no existe, se crea. El archivo se cierra después de escribir todas las cadenas.
type: docs
weight: 1
url: /es/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) método


Agrega cadenas de la colección de cadenas especificada al archivo especificado usando la codificación especificada, escribiendo cada cadena en una nueva línea. Si el archivo especificado no existe, se crea. El archivo se cierra después de escribir todas las cadenas.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo al que se agregarán las cadenas |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Las cadenas que se escribirán en el archivo |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación de caracteres a usar |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)