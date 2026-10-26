---
title: GetDirectories()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una matriz que contiene punteros compartidos a objetos DirectoryInfo que representan todos los directorios ubicados en el directorio representado por el objeto actual.
type: docs
weight: 144
url: /es/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() método


Devuelve una matriz que contiene punteros compartidos a objetos [DirectoryInfo](../) que representan todos los directorios ubicados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) método


Busca los directorios que cumplen con los criterios de búsqueda especificados en el directorio representado por el objeto actual.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los directorios a buscar |

### Valor devuelto

Una matriz de punteros compartidos a objetos [DirectoryInfo](../) que representan los directorios encontrados cuyos nombres coinciden con **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) método


Busca los directorios que cumplen con los criterios de búsqueda especificados ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los directorios a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual |

### Valor devuelto

Una matriz de punteros compartidos a objetos [DirectoryInfo](../) que representan los directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Clase [DirectoryInfo](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)