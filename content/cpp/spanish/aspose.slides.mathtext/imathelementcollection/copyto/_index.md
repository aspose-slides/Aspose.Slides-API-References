---
title: CopyTo()
second_title: Referencia de API de Aspose.Slides para C++
description: Copiar al array especificado.
type: docs
weight: 118
url: /es/aspose.slides.mathtext/imathelementcollection/copyto/
---
## IMathElementCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) method


Copiar al array especificado.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | Array al que copiar. |
| arrayIndex | **int32_t** | Índice donde comenzar a copiar. |
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<IMathElementCollection> collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(collection->get_Count());
collection->CopyTo(destinationArray, 0);
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* clase [IMathElement](../../imathelement/)
* clase [IMathElementCollection](../)
* espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)