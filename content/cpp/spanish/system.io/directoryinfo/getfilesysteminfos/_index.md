---
title: GetFileSystemInfos()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una matriz que contiene punteros compartidos a objetos FileSystemInfo que representan todos los archivos y directorios ubicados en el directorio representado por el objeto actual.
type: docs
weight: 170
url: /es/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() method

Devuelve una matriz que contiene punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan todos los archivos y directorios ubicados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) method

Busca los archivos y directorios que cumplen los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los archivos y directorios a buscar |

### Return Value

Una matriz de punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) method

Busca los archivos y directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo raíz es el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los archivos y directorios a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo raíz es el directorio representado por el objeto actual |

### Return Value

Una matriz de punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Clase [DirectoryInfo](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)