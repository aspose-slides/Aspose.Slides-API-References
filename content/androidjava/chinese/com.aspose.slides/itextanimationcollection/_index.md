---
title: ITextAnimationCollection
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示文本动画的集合。
type: docs
url: /zh/com.aspose.slides/itextanimationcollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

表示文本动画的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引的元素。 |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | 返回所有元素 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```

返回指定索引的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```

返回所有元素

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) 元素。 |

**返回：**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) 的数组