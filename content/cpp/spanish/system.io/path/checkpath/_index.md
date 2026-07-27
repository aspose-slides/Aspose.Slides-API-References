---
title: CheckPath()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si la ruta especificada es válida comprobando si contiene caracteres no válidos. Se lanza una excepción si la ruta contiene caracteres no válidos.
type: docs
weight: 209
url: /es/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) método

Determina si la ruta especificada es válida comprobando si contiene caracteres no válidos. Se lanza una excepción si la ruta contiene caracteres no válidos.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta a verificar |
| msg | const [String](../../../system/string/)\& | El mensaje a pasar al constructor del objeto de excepción |
| allow_empty | **bool** | Especifica si una cadena vacía o nula debe considerarse una ruta correcta (true) o no (false); si este parámetro es false y **path** está vacío se lanza una ArgumentException; si este parámetro es false y **path** es null se lanza una ArgumentNullException |

## Ver también

* Clase [String](../../../system/string/)
* Clase [Path](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)