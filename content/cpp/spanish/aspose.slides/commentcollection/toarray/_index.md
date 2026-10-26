---
title: ToArray()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea y devuelve una matriz con todos los comentarios.
type: docs
weight: 105
url: /es/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() método


Crea y devuelve una matriz con todos los comentarios.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### Valor de retorno

Matriz de [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) método


Crea y devuelve una matriz con todos los comentarios del rango especificado.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **int32_t** | Un índice del primer comentario a devolver. |
| count | **int32_t** | Un número de comentarios a devolver. |

### Valor de retorno

Matriz de [Comment](../../comment/).

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IComment](../../icomment/)
* Clase [CommentCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)