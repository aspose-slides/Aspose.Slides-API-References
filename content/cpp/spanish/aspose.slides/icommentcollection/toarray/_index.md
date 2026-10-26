---
title: ToArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea y devuelve un array con todos los comentarios.
type: docs
weight: 66
url: /es/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() método


Crea y devuelve un array con todos los comentarios.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```


### Valor devuelto

Array de [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) método


Crea y devuelve un array con todos los comentarios del rango especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **int32_t** | Un índice del primer comentario a devolver. |
| count | **int32_t** | El número de comentarios a devolver. |

### Valor devuelto

Array de [IComment](../../icomment/).

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IComment](../../icomment/)
* Clase [ICommentCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)