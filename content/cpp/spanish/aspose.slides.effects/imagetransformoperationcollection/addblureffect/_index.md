---
title: AddBlurEffect()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega el nuevo efecto Blur al final de una colección.
type: docs
weight: 157
url: /es/aspose.slides.effects/imagetransformoperationcollection/addblureffect/
---
## ImageTransformOperationCollection::AddBlurEffect(double, bool) método

Agrega el nuevo efecto [Blur](../../blur/) al final de una colección.

```cpp
System::SharedPtr<IBlur> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBlurEffect(double radius, bool grow) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radius | **double** | El radio del desenfoque. |
| grow | **bool** | Especifica si los límites del objeto deben ampliarse como resultado del desenfoque. True indica que los límites se amplían, mientras que false indica que no se hacen. |

### Valor devuelto

Índice del nuevo efecto de imagen en una colección.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IBlur](../../iblur/)
* Clase [ImageTransformOperationCollection](../)
* Espacio de nombres [Aspose::Slides::Effects](../../)
* Biblioteca [Aspose.Slides](../../../)