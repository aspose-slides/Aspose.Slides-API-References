---
title: EnumerateDirectories()
second_title: Referencia de la API de Aspose.Slides para C++
description: Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios cuya raíz es el directorio especificado.
type: docs
weight: 27
url: /es/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) método

Busca los directorios que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios cuya raíz es el directorio especificado.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ruta completa o relativa al directorio donde buscar |
| searchPattern | const [String](../../../system/string/)\& | Patrón de nombre de los directorios a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio especificado o en todo el árbol de directorios cuya raíz es el directorio especificado |

### Valor devuelto

La colección enumerable de rutas completas de los directorios encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)