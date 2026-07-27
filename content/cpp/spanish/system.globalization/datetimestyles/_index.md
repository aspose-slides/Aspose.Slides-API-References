---
title: DateTimeStyles
second_title: Referencia de API de Aspose.Slides para C++
description: Define opciones de formato de fecha y hora. Banderas de bits.
type: docs
weight: 456
url: /es/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Define opciones de formato de fecha y hora. Banderas de bits.

```cpp
enum class DateTimeStyles : int32_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Predeterminado. |
| AllowLeadingWhite | 1 | Ignorar espacios en blanco iniciales. |
| AllowTrailingWhite | 2 | Ignorar espacios en blanco finales. |
| AllowInnerWhite | 4 | Ignorar espacios en blanco internos. |
| AllowWhiteSpaces | n/a | Ignorar todos los espacios en blanco. |
| NoCurrentDateDefault | 8 | Al analizar una cadena de fecha/hora, si faltan el año, mes y día, establecer la fecha predeterminada a 0001/1/1, en lugar del año/mes/día actual. |
| AdjustToUniversal | 16 | Al analizar una cadena de fecha/hora, si existe un especificador de zona horaria ("GMT","Z","+xxxx","-xxxx"), ajustaremos la hora analizada a GMT. |
| AssumeLocal | 32 | Si no se proporciona zona horaria, usar la zona horaria local. |
| AssumeUniversal | 64 | Si no se proporciona zona horaria, usar UTC. |
| RoundtripKind | 128 | Intentar preservar si la entrada es sin especificar, local o UTC. |

## Ver también

* Espacio de nombres [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)