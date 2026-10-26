---
title: Open()
second_title: Referencia de API de Aspose.Slides para C++
description: Abre el archivo especificado en el modo especificado para lectura y escritura sin compartir.
type: docs
weight: 235
url: /es/system.io/file/open/
---
## File::Open(const String\&, FileMode) método

Abre el archivo especificado en el modo especificado para lectura y escritura y sin compartir.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo a abrir |
| mode | [FileMode](../../filemode/) | Especifica el modo en que se debe abrir el archivo |

### Valor devuelto

Un objeto [FileStream](../../filestream/) asociado al archivo abierto

## File::Open(const String\&, FileMode, FileAccess, FileShare) método

Abre el archivo especificado en el modo especificado, con el tipo de acceso y la opción de uso compartido especificados.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo a abrir |
| mode | [FileMode](../../filemode/) | Especifica el modo en que se debe abrir el archivo |
| access | [FileAccess](../../fileaccess/) | El tipo de acceso solicitado |
| share | [FileShare](../../fileshare/) | El tipo de acceso que otros objetos [FileStream](../../filestream/) tienen al archivo abierto |

### Valor devuelto

Un objeto [FileStream](../../filestream/) asociado al archivo abierto

## Ver también

* Enumeración [FileMode](../../filemode/)
* Enumeración [FileAccess](../../fileaccess/)
* Enumeración [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Clase [String](../../../system/string/)
* Clase [File](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)