---
title: Remove()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina la primera aparición de un objeto específico de la colección.
type: docs
weight: 131
url: /es/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) método


Elimina la primera aparición de un objeto específico de la colección.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El objeto a eliminar de la colección. |

### Valor de retorno

true si *item* se eliminó correctamente de la colección; de lo contrario, false. Este método también devuelve false si *item* no se encuentra en la colección original.
## Observaciones



Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)