---
title: ColorTransformOperation enumeration
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enumeración

Define la operación de transformación de color.

El tipo ColorTransformOperation expone los siguientes miembros:

## Campos

| Campo | Descripción |
| :- | :- |
| TINT | Aplica un tono al color. El parámetro está en el rango entre 0 (color original) y 1 (blanco). |
| SHADE | Oscurece el color. El parámetro está en el rango entre 0 (color original) y 1 (negro). |
| COMPLEMENT | Cambia el color a uno complementario RGB.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Cambia el color a un color invertido.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Cambia el color a un gris con la misma luminosidad. Parámetro ignorado. |
| SET_ALPHA | Define un componente alfa del color. El parámetro está en el rango entre 0 (transparente) y 1 (opaco). |
| ADD_ALPHA | Añade el valor del parámetro a un componente alfa del color. El parámetro está en el rango entre -1 y 1. |
| MULTIPLY_ALPHA | Multiplica un componente alfa por el valor del parámetro. |
| SET_HUE | Cambia el componente de tono del color al valor del parámetro. El parámetro está en el rango entre 0 y 360. |
| ADD_HUE | Añade el valor del parámetro al componente de tono del color. El parámetro está en el rango entre -360 y 360. |
| MULTIPLY_HUE | Multiplica un componente de tono por el valor del parámetro. |
| SET_SATURATION | Cambia el componente de saturación del color al valor del parámetro. El parámetro está en el rango entre 0 y 1. |
| ADD_SATURATION | Añade el valor del parámetro a un componente de saturación del color. El parámetro está en el rango entre -1 y 1. |
| MULTIPLY_SATURATION | Multiplica un componente de saturación por el valor del parámetro. |
| SET_LUMINANCE | Cambia el componente de luminancia del color al valor del parámetro. El parámetro está en el rango entre 0 y 1. |
| ADD_LUMINANCE | Añade el valor del parámetro a un componente de luminancia del color. El parámetro está en el rango entre -1 y 1. |
| MULTIPLY_LUMINANCE | Multiplica un componente de luminancia por el valor del parámetro. |
| SET_RED | Cambia el componente rojo del color al valor del parámetro. El parámetro está en el rango entre 0 y 1. |
| ADD_RED | Añade el valor del parámetro a un componente rojo del color. El parámetro está en el rango entre -1 y 1. |
| MULTIPLY_RED | Multiplica un componente rojo por un parámetro. |
| SET_GREEN | Cambia el componente verde del color al valor del parámetro. El parámetro está en el rango entre 0 y 1. |
| ADD_GREEN | Añade un parámetro a un componente verde del color. El parámetro está en el rango entre -1 y 1. |
| MULTIPLY_GREEN | Multiplica un componente verde por el valor del parámetro. |
| SET_BLUE | Cambia el componente azul del color al valor del parámetro. El parámetro está en el rango entre 0 y 360. |
| ADD_BLUE | Añade el valor del parámetro a un componente azul del color. El parámetro está en el rango entre -1 y 1. |
| MULTIPLY_BLUE | Multiplica un componente azul por el valor del parámetro. |
| GAMMA | Corrección gamma. Parámetro ignorado. |
| INVERSE_GAMMA | Corrección gamma inversa. Parámetro ignorado. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)