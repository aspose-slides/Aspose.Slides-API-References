---
title: register_ink_effect_image method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
将图像注册到用于模拟墨笔视觉效果的自定义图像集合中。  
这些图像在使用特定 [`InkEffectType`](/slides/python-net/zh/aspose.slides.ink/inkeffecttype) 值渲染墨水时使用，  
例如 Galaxy、Rainbow 等。通过提供自己的图像，您可以控制每种墨效的显示方式。

```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/zh/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/zh/aspose.slides/iimage) |  |

### 备注

此方法允许用用户定义的纹理替换默认的墨效纹理，  
当默认资源因许可受限或在运行时不可用时，这尤为有用。  
每个注册的值对必须将一个 [`InkEffectType`](/slides/python-net/zh/aspose.slides.ink/inkeffecttype) 值与相应的  
[`IImage`](/slides/python-net/zh/aspose.slides/iimage) 对象关联（例如 Bitmap，或 Aspose 图像接口）。

### 另见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 类 [`Ink`](/slides/python-net/zh/aspose.slides.ink/ink)
* 枚举 [`InkEffectType`](/slides/python-net/zh/aspose.slides.ink/inkeffecttype)
* 模块 [`aspose.slides.ink`](/slides/python-net/zh/aspose.slides.ink)
* 库 [`Aspose.Slides`](/slides/python-net)