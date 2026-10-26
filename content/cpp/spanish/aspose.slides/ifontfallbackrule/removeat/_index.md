---
title: RemoveAt()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina la fuente FallBack en el índice especificado de la lista.
type: docs
weight: 92
url: /es/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) método


Elimina la fuente FallBack en el índice especificado de la lista.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero de la fuente a eliminar. |
## Observaciones



```cpp
// Crea una regla que contiene una lista de fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Eliminando Tahoma de la lista
newRule->RemoveAt(2);
```


## Ver también

* Clase [IFontFallBackRule](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)