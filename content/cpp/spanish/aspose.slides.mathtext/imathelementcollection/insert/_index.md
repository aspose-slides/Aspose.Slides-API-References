---
title: Insert()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta un elemento matemático en la colección en el índice especificado.
type: docs
weight: 53
url: /es/aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) método


Inserta un elemento matemático en la colección en el índice especificado.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que [IMathElement](../../imathelement/) debe ser insertado. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El [IMathElement](../../imathelement/) a insertar. |
## Observaciones



Ejemplo: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathElementCollection](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)