---
title: Ink
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/ink/
---
## Ink 类

 表示幻灯片上的墨水对象。

### getInkEffectImages {#getInkEffectImages}

| Name | Description |
| --- | --- |
| getInkEffectImages () | 获取用于模拟墨刷视觉效果的自定义图像集合。当使用特定 InkEffectType 值（例如 Galaxy、Rainbow 等）渲染墨水时会使用这些图像。通过提供您自己的图像，您可以控制每种墨水效果的显示方式。此属性允许用用户定义的纹理替换默认的墨水效果纹理，尤其在默认资源受许可证限制或运行时不可用时非常有用。字典中的每个条目必须将 InkEffectType 值与相应的 IImage 对象（例如 Bitmap，或 Aspose 图像接口）关联。 |

 **返回：**
Dictionary


---


### getTraces {#getTraces}

| Name | Description |
| --- | --- |
| getTraces () | 获取 IInk 元素 IInkTrace 中包含的所有痕迹。只读。 |

 **返回：**
[InkTrace](../inktrace)


---