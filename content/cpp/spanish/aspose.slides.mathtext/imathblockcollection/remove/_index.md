---
title: Remove()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina la primera ocurrencia de un objeto específico de la colección/>
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) método

Elimina la primera ocurrencia de un objeto específico de la colección/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | El objeto a eliminar de la colección. |

### Valor de retorno

true si *item* se eliminó correctamente de la colección; de lo contrario, false. Este método también devuelve false si *item* no se encuentra en la colección original/>.

## Observaciones

Ejemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Vea también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBlock](../../imathblock/)
* Clase [IMathBlockCollection](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)