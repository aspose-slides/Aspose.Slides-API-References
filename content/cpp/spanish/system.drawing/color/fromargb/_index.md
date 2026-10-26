---
title: FromArgb()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una instancia de la clase Color que representa el color especificado.
type: docs
weight: 235
url: /es/system.drawing/color/fromargb/
---
## Color::FromArgb(int) método

Construye una instancia de la clase [Color](../) que representa el color especificado.

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb | int | Un valor ARGB de 32 bits del color que será representado por el objeto que se está construyendo |

### Valor de retorno

Un objeto que representa el color especificado.

## Color::FromArgb(int, int, int, int) método

Construye una instancia de la clase [Color](../) que representa el color especificado.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | int | Un valor del componente alfa del color |
| red | int | Un valor del componente rojo del color |
| green | int | Un valor del componente verde del color |
| blue | int | Un valor del componente azul del color |

### Valor de retorno

Un objeto que representa el color especificado.

## Color::FromArgb(int, int, int) método

Construye una instancia de la clase [Color](../) que representa el color especificado con el componente alfa establecido a 0xFF.

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| red | int | Un valor del componente rojo del color |
| green | int | Un valor del componente verde del color |
| blue | int | Un valor del componente azul del color |

### Valor de retorno

Un objeto que representa el color especificado.

## Color::FromArgb(int, Color) método

Construye una instancia de la clase [Color](../) que representa el color especificado.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | int | Un valor del componente alfa del color |
| base_color | [Color](../) | Una instancia del objeto [Color](../) que representa los componentes rojo, verde y azul del color que será representado por el objeto que se está creando |

### Valor de retorno

Un objeto que representa el color especificado.

## Véase también

* Clase [Color](../)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)