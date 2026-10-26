---
title: ToArray()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea y devuelve una matriz con todas las fuentes de reserva para esta regla.
type: docs
weight: 105
url: /es/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() método


Crea y devuelve una matriz con todas las fuentes de reserva para esta regla.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### Valor de retorno

Array of [System::String](../../../system/string/)
## Observaciones



```cpp
// Crea una regla que contiene una lista de fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Obtiene todos los nombres de fuentes como matriz
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) método


Crea y devuelve una matriz con todas las fuentes de reserva del rango especificado en la lista.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **int32_t** | Un índice de la primera fuente a añadir. |
| count | **int32_t** | Una cantidad de fuentes a añadir. |

### Valor de retorno

Array of [System::String](../../../system/string/)
## Observaciones



```cpp
// Crea una regla que contiene una lista de fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Obtiene los dos últimos nombres de fuentes como matriz
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [IFontFallBackRule](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)