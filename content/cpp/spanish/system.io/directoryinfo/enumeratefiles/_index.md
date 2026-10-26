---
title: EnumerateFiles()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una colección enumerada que contiene todos los archivos ubicados en el directorio representado por el objeto actual.
type: docs
weight: 118
url: /es/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() método

Devuelve una colección enumerada que contiene todos los archivos ubicados en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) método

Busca los archivos que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los archivos a buscar |

### Valor devuelto

La colección enumerada de punteros compartidos a objetos [FileInfo](../../fileinfo/) que representan los archivos encontrados cuyos nombres coinciden con **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) método

Busca los archivos que cumplen con los criterios de búsqueda especificados ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo origen es el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los archivos a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo origen es el directorio representado por el objeto actual |

### Valor devuelto

La colección enumerada de punteros compartidos a objetos [FileInfo](../../fileinfo/) que representan los archivos encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enumeración [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Clase [DirectoryInfo](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)