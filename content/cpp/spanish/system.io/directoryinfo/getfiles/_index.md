---
title: GetFiles()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una matriz que contiene punteros compartidos a objetos FileInfo que representan todos los directorios ubicados en el directorio representado por el objeto actual.
type: docs
weight: 157
url: /es/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() método


Devuelve una matriz que contiene punteros compartidos a los objetos [FileInfo](../../fileinfo/) que representan todos los directorios ubicados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) método


Busca los archivos que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los archivos a buscar |

### Valor devuelto

Una matriz de punteros compartidos a los objetos [FileInfo](../../fileinfo/) que representan los archivos encontrados cuyos nombres coinciden con **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) método


Busca los archivos que cumplen con los criterios de búsqueda especificados ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo nodo raíz es el directorio representado por el objeto actual.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los archivos a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuyo nodo raíz es el directorio representado por el objeto actual |

### Valor devuelto

Una matriz de punteros compartidos a los objetos [FileInfo](../../fileinfo/) que representan los archivos encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enumeración [SearchOption](../../searchoption/)
* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Definición de tipo [FileInfoPtr](../../../system/fileinfoptr/)
* Clase [DirectoryInfo](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)