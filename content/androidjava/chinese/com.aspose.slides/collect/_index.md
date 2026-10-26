---
title: Collect
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示一个用于从 . 收集不同类型模型对象的方法组。
type: docs
url: /zh/com.aspose.slides/collect/
---
**继承:**
java.lang.Object
```
public class Collect
```

表示一组用于从 [Presentation](../../com.aspose.slides/presentation) 收集不同类型模型对象的方法。

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
## Constructors

| Constructor | Description |
| --- | --- |
| [Collect()](#Collect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Collects all instances of [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)

Collects all instances of [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation).

--------------------

Presentation pres = new Presentation("pres.pptx");
 try {
     for (IShape shape : Collect.shapes(pres))
     {
         // if the shape is AutoShape, add a black solid border
         if (shape instanceof AutoShape)
         {
             AutoShape autoShape = (AutoShape)shape;
             autoShape.getLineFormat().setStyle(LineStyle.Single);
             autoShape.getLineFormat().setWidth(10f);
             autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
             autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
         }
     }
     pres.save("pres-out.pptx", SaveFormat.Pptx);
 } finally {
     if (pres != null) pres.dispose();
 }

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 用于收集形状的演示文稿 |

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - 演示文稿中包含的所有形状的集合