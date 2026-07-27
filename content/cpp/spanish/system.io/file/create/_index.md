---
title: Create()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo archivo (o sobrescribe el existente) y lo abre para acceso de lectura y escritura usando el tamaño de búfer y las opciones especificadas.
type: docs
weight: 53
url: /es/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) método

Crea un nuevo archivo (o sobrescribe el existente) y lo abre para acceso de lectura y escritura usando el tamaño de búfer y las opciones especificadas.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo que se va a crear o sobrescribir |
| bufferSize | **int32_t** | El número de bytes almacenados en búfer al leer y escribir el archivo |
| options | [FileOptions](../../fileoptions/) | Especifica cómo crear o sobrescribir el archivo |

### Valor de retorno

Un puntero compartido al objeto [FileStream](../../filestream/) asociado con el archivo especificado

## Ver también

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)