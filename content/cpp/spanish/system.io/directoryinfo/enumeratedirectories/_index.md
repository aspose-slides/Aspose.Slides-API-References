---
title: EnumerateDirectories()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una colección enumerable que contiene todos los directorios ubicados en el directorio representado por el objeto actual.
type: docs
weight: 105
url: /es/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() método

Devuelve una colección enumerable que contiene todos los directorios ubicados en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```
## DirectoryInfo::EnumerateDirectories(const String\&) método

Busca los directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los directorios a buscar |

### Valor devuelto

La colección enumerable de punteros compartidos a objetos [DirectoryInfo](../) que representan los directorios encontrados cuyo nombre coincide con **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) método

Busca los directorios que cumplen con los criterios de búsqueda especificados ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los directorios a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual |

### Valor devuelto

La colección enumerable de punteros compartidos a objetos [DirectoryInfo](../) que representan los directorios encontrados cuyo nombre coincide con **searchPattern**

## Ver también

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Clase [DirectoryInfo](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)