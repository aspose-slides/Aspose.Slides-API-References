---
title: IInk
second_title: Aspose.Slides 的 Java API 參考
description: 代表投影片上的墨跡物件。
type: docs
url: /zh-hant/com.aspose.slides/iink/
---
**已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

代表投影片上的墨跡物件。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTraces()](#getTraces--) | 取得 IInk 元素 [IInkTrace](../../com.aspose.slides/iinktrace) 中的所有痕跡。 |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


取得 IInk 元素 [IInkTrace](../../com.aspose.slides/iinktrace) 中的所有痕跡。唯讀。

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