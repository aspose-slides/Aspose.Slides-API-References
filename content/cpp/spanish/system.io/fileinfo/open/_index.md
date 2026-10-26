---
title: Open()
second_title: Referencia de la API de Aspose.Slides para C++
description: Abre el archivo representado por el objeto actual en el modo especificado para lectura y escritura y sin compartir.
type: docs
weight: 183
url: /es/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) método


Abre el archivo representado por el objeto actual en el modo especificado para lectura y escritura y sin compartir.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Especifica el modo en que abrir el flie |

### Valor de retorno

Un objeto [FileStream](../../filestream/) asociado al archivo representado por el objeto actual

## FileInfo::Open(FileMode, FileAccess) método


Abre el archivo representado por el objeto actual en el modo especificado, con el tipo de acceso especificado y sin compartir.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Especifica el modo en que abrir el flie |
| access | [FileAccess](../../fileaccess/) | El tipo de acceso solicitado |

### Valor de retorno

Un objeto [FileStream](../../filestream/) asociado al archivo representado por el objeto actual

## FileInfo::Open(FileMode, FileAccess, FileShare) método


Abre el archivo representado por el objeto actual en el modo especificado, con el tipo de acceso especificado y la opción de compartir.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Especifica el modo en que abrir el flie |
| access | [FileAccess](../../fileaccess/) | El tipo de acceso solicitado |
| share | [FileShare](../../fileshare/) | El tipo de acceso que otros objetos [FileStream](../../filestream/) tienen al archivo abierto |

### Valor de retorno

Un objeto [FileStream](../../filestream/) asociado al archivo representado por el objeto actual

## Ver también

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)