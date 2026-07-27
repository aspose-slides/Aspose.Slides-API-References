---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega un elemento matemático al final de la colección.
type: docs
weight: 79
url: /es/aspose.slides.mathtext/mathblock/add/
---
## MathBlock::Add(System::SharedPtr\<IMathElement\>) método

Agrega un elemento matemático al final de la colección.

```cpp
void Aspose::Slides::MathText::MathBlock::Add(System::SharedPtr<IMathElement> item) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El [IMathElement](../../imathelement/) que se agregará al final de la colección. |
## Observaciones



Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
mathBlock->Add(System::MakeObject<MathematicalText>(u"+"));
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)