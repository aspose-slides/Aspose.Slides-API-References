---
title: GetFileSystemEntries()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca los archivos y directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios cuya raíz es el directorio especificado.
type: docs
weight: 92
url: /es/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) método

Busca los archivos y directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios cuya raíz es el directorio especificado.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ruta completa o relativa al directorio en el que buscar |
| searchPattern | const [String](../../../system/string/)\& | El patrón de nombre de los archivos y directorios a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio especificado o en todo el árbol de directorios cuya raíz es el directorio especificado |

### Valor devuelto

Una matriz de rutas completas de los archivos y directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [Directory](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)