---
title: Collect
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示一組旨在從 中收集不同類型模型物件的方法。
type: docs
url: /zh-hant/com.aspose.slides/collect/
---
**繼承：**
java.lang.Object
```
public class Collect
```

表示一組旨在從 [Presentation](../../com.aspose.slides/presentation) 收集不同類型模型物件的方法。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... 變更形狀格式或其他屬性
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [Collect()](#Collect--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | 在 [Presentation](../../com.aspose.slides/presentation) 中收集所有 [Shape](../../com.aspose.slides/shape) 實例。 |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


在 [Presentation](../../com.aspose.slides/presentation) 中收集所有 [Shape](../../com.aspose.slides/shape) 實例。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // 如果形狀是 AutoShape，則添加黑色實線邊框
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用於收集圖形的簡報 |

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - 包含於簡報中的所有圖形的集合