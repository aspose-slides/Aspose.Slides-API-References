---
title: ColorTransformOperation
second_title: Referencia de la API de Aspose.Slides para C++
description: Define la operación de transformación de color.
type: docs
weight: 5747
url: /es/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

Define la operación de transformación de color.

```cpp
enum class ColorTransformOperation
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Tint | 0 | Aplica un tono al color. El parámetro está en el rango entre 0 (color original) y 1 (blanco). |
| Shade | 1 | Oscurece el color. El parámetro está en el rango entre 0 (color original) y 1 (negro). |
| Complement | 2 | Cambia el color a uno complementario RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Cambia el color a un color invertido. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Cambia el color a un gris con la misma luminosidad. Parámetro ignorado. |
| SetAlpha | 5 | Define un componente alfa del color. El parámetro está en el rango entre 0 (transparente) y 1 (opaco). |
| AddAlpha | 6 | Añade el valor de un parámetro a un componente alfa del color. El parámetro está en el rango entre -1 y 1. |
| MultiplyAlpha | 7 | Multiplica un componente alfa por el valor de un parámetro. |
| SetHue | 8 | Cambia el componente matiz del color al valor de un parámetro. El parámetro está en el rango entre 0 y 360. |
| AddHue | 9 | Añade el valor del parámetro al componente matiz del color. El parámetro está en el rango entre -360 y 360. |
| MultiplyHue | 10 | Multiplica un componente matiz por el valor de un parámetro. |
| SetSaturation | 11 | Cambia el componente saturación del color al valor de un parámetro. El parámetro está en el rango entre 0 y 1. |
| AddSaturation | 12 | Añade el valor del parámetro al componente saturación del color. El parámetro está en el rango entre -1 y 1. |
| MultiplySaturation | 13 | Multiplica un componente saturación por el valor de un parámetro. |
| SetLuminance | 14 | Cambia el componente luminancia del color al valor de un parámetro. El parámetro está en el rango entre 0 y 1. |
| AddLuminance | 15 | Añade el valor del parámetro al componente luminancia del color. El parámetro está en el rango entre -1 y 1. |
| MultiplyLuminance | 16 | Multiplica un componente luminancia por el valor de un parámetro. |
| SetRed | 17 | Cambia el componente rojo del color al valor de un parámetro. El parámetro está en el rango entre 0 y 1. |
| AddRed | 18 | Añade el valor del parámetro al componente rojo del color. El parámetro está en el rango entre -1 y 1. |
| MultiplyRed | 19 | Multiplica un componente rojo por un parámetro. |
| SetGreen | 20 | Cambia el componente verde del color al valor del parámetro. El parámetro está en el rango entre 0 y 1. |
| AddGreen | 21 | Añade un parámetro al componente verde del color. El parámetro está en el rango entre -1 y 1. |
| MultiplyGreen | 22 | Multiplica un componente verde por el valor de un parámetro. |
| SetBlue | 23 | Cambia el componente azul del color al valor de un parámetro. El parámetro está en el rango entre 0 y 360. |
| AddBlue | 24 | Añade el valor del parámetro al componente azul del color. El parámetro está en el rango entre -1 y 1. |
| MultiplyBlue | 25 | Multiplica un componente azul por el valor de un parámetro. |
| Gamma | 26 | Corrección gamma. Parámetro ignorado. |
| InverseGamma | 27 | Corrección gamma inversa. Parámetro ignorado. |

## Ver también

* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)