---
title: WriteAllLines()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo archivo de texto o sobrescribe el existente y escribe todas las cadenas de la colección enumerable de cadenas especificada en él, cada cadena en una nueva línea, usando la codificación especificada.
type: docs
weight: 456
url: /es/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) método

Crea un nuevo archivo de texto o sobrescribe el existente y escribe todas las cadenas de la colección enumerable de cadenas especificada en él, cada cadena en una nueva línea, usando la codificación especificada.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | El archivo a crear o sobrescribir |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Una colección enumerable de cadenas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación de caracteres a usar |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) método

Crea un nuevo archivo de texto o sobrescribe el existente y escribe todas las cadenas del arreglo de cadenas especificado en él, cada cadena en una nueva línea, usando la codificación especificada.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | El archivo a crear o sobrescribir |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Una matriz de cadenas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación de caracteres a usar |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Clase [File](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)