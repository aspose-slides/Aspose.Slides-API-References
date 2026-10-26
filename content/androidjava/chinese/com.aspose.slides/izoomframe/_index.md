---
title: IZoomFrame
second_title: Aspose.Slides 适用于 Android 的 Java API 参考
description: 表示幻灯片中的 Slide Zoom 对象。
type: docs
url: /zh/com.aspose.slides/izoomframe/
---
**所有已实现的接口：**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

表示幻灯片中的 Slide Zoom 对象。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | 获取或设置 Slide Zoom 对象链接到的幻灯片对象。 |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | 获取或设置 Slide Zoom 对象链接到的幻灯片对象。 |

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

获取或设置 Slide Zoom 对象链接到的幻灯片对象。读/写 [ISlide](../../com.aspose.slides/islide)。

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
获取或设置 Slide Zoom 对象链接到的幻灯片对象。读/写 [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> 下例演示了更改目标幻灯片并为 Slide Zoom 对象创建新图像：
>   
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |