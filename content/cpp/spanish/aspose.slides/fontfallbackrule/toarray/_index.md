---
title: ToArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea y devuelve una matriz con todas las fuentes FallBack para esta regla.
type: docs
weight: 144
url: /es/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() method


Crea y devuelve una matriz con todas las fuentes FallBack para esta regla.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```


### Valor devuelto

Matriz de [System::String](../../../system/string/)
## Observaciones



```cpp
// Crea una regla que contiene una lista de fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Obtén todos los nombres de fuentes como una matriz.
ArrayPtr<String> fontNames = newRule->ToArray();
```


## FontFallBackRule::ToArray(int32_t, int32_t) method


Crea y devuelve una matriz con todas las fuentes FallBack del rango especificado en la lista.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **int32_t** | Un índice de la primera fuente a añadir. |
| count | **int32_t** | Una cantidad de fuentes a añadir. |

### Valor devuelto

Matriz de [System::String](../../../system/string/)
## Observaciones



```cpp
// Crea una regla que contiene una lista de fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Obtén los dos últimos nombres de fuentes como una matriz.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)