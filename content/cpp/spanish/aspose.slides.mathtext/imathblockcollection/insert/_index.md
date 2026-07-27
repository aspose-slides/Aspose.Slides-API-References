---
title: Insert()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta IMathBlock en la colección en el índice especificado.
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) método

Inserta [IMathBlock](../../imathblock/) en la colección en el índice especificado.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se debe insertar un elemento. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | El [IMathBlock](../../imathblock/) a insertar. |
## Observaciones

Ejemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)