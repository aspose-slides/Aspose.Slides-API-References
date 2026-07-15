---
title: Ink
second_title: Aspose.Slides for Android 之 Java API 參考
description: 表示投影片上的墨跡物件。
type: docs
url: /zh-hant/com.aspose.slides/ink/
---
**繼承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有已實作的介面:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

表示投影片上的墨跡物件。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getTraces()](#getTraces--) | 取得 IInk 元素 [IInkTrace](../../com.aspose.slides/iinktrace) 中包含的所有軌跡。 |
| [getInkEffectImages()](#getInkEffectImages--) | 取得用於模擬墨筆視覺效果的自訂影像集合。 |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

取得 IInk 元素 [IInkTrace](../../com.aspose.slides/iinktrace) 中包含的所有軌跡。唯讀。

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

取得用於模擬墨筆視覺效果的自訂影像集合。這些影像在使用特定的 [InkEffectType](../../com.aspose.slides/inkeffecttype) 值（例如 Galaxy、Rainbow 等）渲染墨跡時會被使用。透過提供自訂影像，您可以控制每種墨跡效果的呈現方式。

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

此屬性允許以使用者自訂的材質取代預設的墨跡效果紋理，這在預設資產受授權限制或在執行時不可用時特別有用。字典中的每個條目必須將 [InkEffectType](../../com.aspose.slides/inkeffecttype) 值與相應的 [IImage](../../com.aspose.slides/iimage) 物件（例如 Bitmap，或 Aspose 影像介面）關聯起來。

**返回：**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>