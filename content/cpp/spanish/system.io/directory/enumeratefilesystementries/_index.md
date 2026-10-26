---
title: EnumerateFileSystemEntries()
second_title: Referencia de la API de Aspose.Slides para C++
description: Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios cuya raíz es el directorio especificado.
type: docs
weight: 53
url: /es/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String&, const String&, SearchOption) método


Busca los archivos y directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio indicado o en todo el árbol de directorios cuya raíz es el directorio especificado.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Ruta completa o relativa al directorio en el que buscar |
| searchPattern | const [String](../../../system/string/)& | Patrón de nombre de los archivos y directorios a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado |

### Valor de retorno

La colección enumerable de rutas completas de los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enumeración [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Clase [String](../../../system/string/)
* Clase [Directory](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)