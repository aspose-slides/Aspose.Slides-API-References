---
title: get_InkEffectImages()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la colección de imágenes personalizadas usadas para simular efectos visuales de los pinceles de tinta. Estas imágenes se utilizan al renderizar tinta con valores específicos de InkEffectType, como Galaxy, Rainbow, etc. Al proporcionar sus propias imágenes, puede controlar cómo aparece cada efecto de tinta.
type: docs
weight: 14
url: /es/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() método

Obtiene la colección de imágenes personalizadas usadas para simular efectos visuales de los pinceles de tinta. Estas imágenes se utilizan al renderizar tinta con valores específicos de [InkEffectType](../../inkeffecttype/), como Galaxy, Rainbow, etc. Al proporcionar sus propias imágenes, puede controlar cómo aparece cada efecto de tinta.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Observaciones

Esta propiedad permite reemplazar las texturas de efecto de tinta predeterminadas por otras definidas por el usuario, lo que es particularmente útil cuando los recursos predeterminados están restringidos por licencias o no están disponibles en tiempo de ejecución.

Cada entrada en el diccionario debe asociar un valor [InkEffectType](../../inkeffecttype/) con un objeto [IImage](../../../aspose.slides/iimage/) correspondiente (p. ej., Bitmap, o una interfaz de imagen **Aspose**).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Ver también

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)