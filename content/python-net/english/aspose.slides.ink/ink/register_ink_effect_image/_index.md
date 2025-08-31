---
title: register_ink_effect_image method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---


## register_ink_effect_image {#asposeslidesinkinkeffecttype-asposeslidesiimage}
Registers an image to collection of custom images used to simulate visual effects for ink brushes.
            These images are used when rendering ink with specific [`InkEffectType`](/slides/python-net/aspose.slides.ink/inkeffecttype) values,
            such as Galaxy, Rainbow, etc. By providing your own images, you can control how each ink effect appears.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/aspose.slides/iimage) |  |

### Remarks

This method allows replacing the default ink effect textures with user-defined ones,
            which is particularly useful when default assets are restricted by licensing or unavailable at runtime.
            Each registered value pair must associate an [`InkEffectType`](/slides/python-net/aspose.slides.ink/inkeffecttype) value with a corresponding
[`IImage`](/slides/python-net/aspose.slides/iimage) object (e.g., Bitmap, or an Aspose image interface).



### See Also
* class [`IImage`](/slides/python-net/aspose.slides/iimage)
* class [`Ink`](/slides/python-net/aspose.slides.ink/ink)
* enumeration [`InkEffectType`](/slides/python-net/aspose.slides.ink/inkeffecttype)
* module [`aspose.slides.ink`](/slides/python-net/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)

