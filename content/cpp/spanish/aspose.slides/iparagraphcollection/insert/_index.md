---
title: Insert()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta un Paragraph en la colección en el índice especificado.
type: docs
weight: 40
url: /es/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) método

Inserta un [Paragraph](../../paragraph/) en la colección en el índice especificado.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que [Paragraph](../../paragraph/) debe insertarse. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | El [Paragraph](../../paragraph/) a insertar. |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) método

Inserta un contenido de [ParagraphCollection](../../paragraphcollection/) en la colección en el índice especificado.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que los párrafos deben insertarse. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | Los párrafos a insertar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IParagraph](../../iparagraph/)
* Clase [IParagraphCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)