---
title: get_InkEffectImages()
second_title: Aspose.Slides for C++ API 参考
description: 获取用于模拟墨水笔刷视觉效果的自定义图像集合。这些图像在使用特定 InkEffectType 值（例如 Galaxy、Rainbow 等）渲染墨水时使用。通过提供您自己的图像，您可以控制每个墨水效果的显示方式。
type: docs
weight: 14
url: /zh/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() 方法

获取用于模拟墨水笔刷视觉效果的自定义图像集合。当使用特定[InkEffectType](../../inkeffecttype/)值（例如 Galaxy、Rainbow 等）渲染墨水时会使用这些图像。通过提供您自己的图像，您可以控制每个墨水效果的显示方式。

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## 备注

此属性允许用用户定义的纹理替换默认的墨水效果纹理，这在默认资源受许可限制或在运行时不可用时特别有用。

字典中的每个条目必须将 [InkEffectType](../../inkeffecttype/) 值与相应的 [IImage](../../../aspose.slides/iimage/) 对象关联（例如 Bitmap，或 **Aspose** 图像接口）。

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## 另请参见

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)