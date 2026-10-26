---
title: register_ink_effect_image method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Registra una imagen en la colección de imágenes personalizadas utilizadas para simular efectos visuales de los pinceles de tinta.
Estas imágenes se usan al renderizar tinta con valores específicos [`InkEffectType`](/slides/python-net/es/aspose.slides.ink/inkeffecttype), como Galaxy, Rainbow, etc. Al proporcionar tus propias imágenes, puedes controlar cómo aparece cada efecto de tinta.

```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/es/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/es/aspose.slides/iimage) |  |

### Observaciones

Este método permite reemplazar las texturas de efecto de tinta predeterminadas por unas definidas por el usuario, lo cual es particularmente útil cuando los recursos predeterminados están restringidos por licencias o no están disponibles en tiempo de ejecución. Cada par de valores registrado debe asociar un valor [`InkEffectType`](/slides/python-net/es/aspose.slides.ink/inkeffecttype) con un objeto [`IImage`](/slides/python-net/es/aspose.slides/iimage) correspondiente (p.ej., Bitmap, o una interfaz de imagen de Aspose).

### Ver también
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* clase [`Ink`](/slides/python-net/es/aspose.slides.ink/ink)
* enumeración [`InkEffectType`](/slides/python-net/es/aspose.slides.ink/inkeffecttype)
* módulo [`aspose.slides.ink`](/slides/python-net/es/aspose.slides.ink)
* biblioteca [`Aspose.Slides`](/slides/python-net)