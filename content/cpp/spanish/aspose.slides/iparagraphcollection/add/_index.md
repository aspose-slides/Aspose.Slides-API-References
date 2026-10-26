---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega un Paragraph al final de la colección.
type: docs
weight: 27
url: /es/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) método

Agrega un [Paragraph](../../paragraph/) al final de la colección.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | El [Paragraph](../../paragraph/) que se agregará al final de la colección. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) método

Agrega un contenido de [ParagraphCollection](../../paragraphcollection/) al final de la colección.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | El [ParagraphCollection](../../paragraphcollection/) que se agregará al final de la colección. |

### Valor de retorno

El índice en el que se ha agregado el [Paragraph](../../paragraph/) o -1 si no hay nada que agregar.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IParagraph](../../iparagraph/)
* Clase [IParagraphCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)