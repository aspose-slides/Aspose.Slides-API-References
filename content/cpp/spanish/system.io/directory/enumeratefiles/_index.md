---
title: EnumerateFiles()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios cuya raíz es el directorio especificado.
type: docs
weight: 40
url: /es/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) método

Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios cuyo raíz es el directorio especificado.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ruta completa o relativa al directorio donde buscar |
| searchPattern | const [String](../../../system/string/)\& | Patrón de nombre de los archivos a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio especificado o en todo el árbol de directorios cuyo raíz es el directorio especificado |

### Valor devuelto

La colección enumerable de rutas completas de los archivos encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Clase [String](../../../system/string/)
* Clase [Directory](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)