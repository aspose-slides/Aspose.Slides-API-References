---
title: STDIOStreamPositionPreference
second_title: Referencia de la API de Aspose.Slides para C++
description: "Determina qué posición en el flujo es preferible como posición común de lectura y escritura cuando std::basic_iostream y sus descendientes tendrán diferentes posiciones de lectura y escritura al crear el contenedor."
type: docs
weight: 586
url: /es/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference enum

Determina qué posición en el flujo es preferible como posición común de lectura y escritura cuando std::basic_iostream y sus descendientes tendrán diferentes posiciones de lectura y escritura al momento de crear el contenedor.

```cpp
enum class STDIOStreamPositionPreference
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Zero | 0 | La posición cero se establecerá como posición de lectura y escritura. |
| ReadPosition | 1 | La posición gptr se establecerá como posición de lectura y escritura. |
| WritePosition | 2 | La posición pptr se establecerá como posición de lectura y escritura. |

## Ver también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)