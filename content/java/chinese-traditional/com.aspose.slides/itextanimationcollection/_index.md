---
title: ITextAnimationCollection
second_title: Aspose.Slides for Java API 參考
description: 表示文字動畫的集合。
type: docs
url: /zh-hant/com.aspose.slides/itextanimationcollection/
---
**所有實作的介面:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

表示文字動畫的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據索引返回元素。 |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | 返回所有元素 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


根據索引返回元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


返回所有元素

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) 元素。 |

**返回值:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) 的陣列