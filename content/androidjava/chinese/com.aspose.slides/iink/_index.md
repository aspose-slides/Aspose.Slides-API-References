---
title: IInk
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片上的墨水对象。
type: docs
url: /zh/com.aspose.slides/iink/
---
**所有实现的接口：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

表示幻灯片上的墨水对象。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTraces()](#getTraces--) | 获取 IInk 元素 [IInkTrace](../../com.aspose.slides/iinktrace) 中包含的所有痕迹。 |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


获取 IInk 元素 [IInkTrace](../../com.aspose.slides/iinktrace) 中包含的所有痕迹。只读。

--------------------

> ```
> 示例：
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