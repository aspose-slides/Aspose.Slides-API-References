---
title: GetFiles()
second_title: Referencia de la API de Aspose.Slides para C++
description: Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado.
type: docs
weight: 79
url: /es/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) método

Busca los archivos que cumplen con los criterios de búsqueda especificados, ya sea en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ruta completa o relativa al directorio en el que buscar |
| searchPattern | const [String](../../../system/string/)\& | Patrón de nombre de los archivos a buscar |
| searchOption | [SearchOption](../../searchoption/) | Especifica si la búsqueda debe realizarse solo en el directorio especificado o en todo el árbol de directorios con raíz en el directorio especificado |

### Valor de retorno

Una matriz de rutas completas de los archivos encontrados cuyos nombres coinciden con **searchPattern**

## Ver también

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [Directory](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)