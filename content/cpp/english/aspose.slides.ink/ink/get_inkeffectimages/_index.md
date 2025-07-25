---
title: get_InkEffectImages()
second_title: Aspose.Slides for C++ API Reference
description: Gets the collection of custom images used to simulate visual effects for ink brushes. These images are used when rendering ink with specific InkEffectType values, such as Galaxy, Rainbow, etc. By providing your own images, you can control how each ink effect appears.
type: docs
weight: 14
url: /aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() method


Gets the collection of custom images used to simulate visual effects for ink brushes. These images are used when rendering ink with specific [InkEffectType](../../inkeffecttype/) values, such as Galaxy, Rainbow, etc. By providing your own images, you can control how each ink effect appears.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Remarks


This property allows replacing the default ink effect textures with user-defined ones, which is particularly useful when default assets are restricted by licensing or unavailable at runtime.

Each entry in the dictionary must associate an [InkEffectType](../../inkeffecttype/) value with a corresponding [IImage](../../../aspose.slides/iimage/) object (e.g., Bitmap, or an **Aspose** image interface). 


```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## See Also

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)