---
title: EnumerateFileSystemInfos()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una colección enumerable que contiene todos los archivos y directorios ubicados en el directorio representado por el objeto actual.
type: docs
weight: 131
url: /es/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() método


Devuelve una colección enumerable que contiene todos los archivos y directorios ubicados en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) método


Busca los archivos y directorios que cumplen el criterio de búsqueda especificado en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los archivos y directorios a buscar |

### Valor devuelto

La colección enumerable de punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) método


Busca los archivos y directorios que cumplen el criterio de búsqueda especificado ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los archivos y directorios a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual |

### Valor devuelto

La colección enumerable de punteros compartidos a objetos [FileSystemInfo](../../filesysteminfo/) que representan los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)