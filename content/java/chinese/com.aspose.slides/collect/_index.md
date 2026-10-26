---
title: Collect
second_title: Aspose.Slides for Java API 参考文档
description: 表示一组旨在从中收集不同类型模型对象的方法。
type: docs
url: /zh/com.aspose.slides/collect/
---
**继承：**
java.lang.Object
```
public class Collect
```

表示一组旨在从 [Presentation](../../com.aspose.slides/presentation) 收集不同类型模型对象的方法。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... 更改形状格式或其他属性
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Collect()](#Collect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | 收集[Presentation](../../com.aspose.slides/presentation)中的所有[Shape](../../com.aspose.slides/shape)实例。 |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

收集[Presentation](../../com.aspose.slides/presentation)中的所有[Shape](../../com.aspose.slides/shape)实例。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // 如果形状是 AutoShape，则添加黑色实线边框
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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于收集形状的演示文稿 |

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - 演示文稿中包含的所有形状的集合