---
title: FileStream()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase FileStream y la inicializa con los parámetros especificados.
type: docs
weight: 1
url: /es/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) constructor

Construye una nueva instancia de la clase [FileStream](../) y la inicializa con los parámetros especificados.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo a abrir. |
| mode | [FileMode](../../filemode/) | Especifica el modo en que se debe abrir el archivo. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor

Construye una nueva instancia de la clase [FileStream](../) y la inicializa con los parámetros especificados.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo a abrir. |
| mode | [FileMode](../../filemode/) | Especifica el modo en que se debe abrir el archivo. |
| access | [FileAccess](../../fileaccess/) | El tipo de acceso solicitado. |
| share | [FileShare](../../fileshare/) | El tipo de acceso que otros objetos [FileStream](../) tienen al archivo abierto. |
| buffer_size | **int32_t** | El número de bytes almacenados en búfer durante las operaciones de lectura y escritura. |
| options | [FileOptions](../../fileoptions/) | Opciones adicionales. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor

Construye una nueva instancia de la clase [FileStream](../) y la inicializa con los parámetros especificados.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo a abrir. |
| mode | [FileMode](../../filemode/) | Especifica el modo en que se debe abrir el archivo. |
| access | [FileAccess](../../fileaccess/) | El tipo de acceso solicitado. |
| share | [FileShare](../../fileshare/) | El tipo de acceso que otros objetos [FileStream](../) tienen al archivo abierto. |
| buffer_size | **int32_t** | El número de bytes almacenados en búfer durante las operaciones de lectura y escritura. |
| useAsync | **bool** | Especifica si se debe usar I/O asíncrono o I/O sincrónico. |

## Comentarios

El sistema operativo subyacente podría no admitir I/O asíncrono. 

## FileStream::FileStream(const FileStream\&) constructor

```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Ver también

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [String](../../../system/string/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)