---
title: Ink
second_title: Aspose.Slides for Java API 参考
description: 表示幻灯片上的墨水对象。
type: docs
url: /zh/com.aspose.slides/ink/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有实现的接口:**  
[com.aspose.slides.IInk](../../com.aspose.slides/iink)  
```
public class Ink extends GraphicalObject implements IInk
```

表示幻灯片上的墨水对象。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTraces()](#getTraces--) | 获取 IInk 元素 [IInkTrace](../../com.aspose.slides/iinktrace) 中包含的所有痕迹。 |
| [getInkEffectImages()](#getInkEffectImages--) | 获取用于模拟墨水笔刷视觉效果的自定义图像集合。 |

### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

获取 IInk 元素 [IInkTrace](../../com.aspose.slides/iinktrace) 中包含的所有痕迹。只读。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**  
com.aspose.slides.IInkTrace[]

### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

获取用于模拟墨水笔刷视觉效果的自定义图像集合。这些图像在使用特定 [InkEffectType](../../com.aspose.slides/inkeffecttype) 值（例如 Galaxy、Rainbow 等）渲染墨水时使用。通过提供您自己的图像，您可以控制每个墨水效果的呈现方式。

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

此属性允许使用用户定义的纹理替换默认的墨水效果纹理，这在默认资源受许可证限制或在运行时不可用时特别有用。字典中的每个条目必须将 [InkEffectType](../../com.aspose.slides/inkeffecttype) 值与相应的 [IImage](../../com.aspose.slides/iimage) 对象关联（例如 Bitmap，或 Aspose 图像接口）。

**返回：**  
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>