---
title: ITextAnimationCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示文字動畫的集合。
type: docs
url: /zh-hant/com.aspose.slides/itextanimationcollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

表示文字動畫的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 回傳指定索引的元素。 |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | 回傳所有元素 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


回傳指定索引的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


回傳所有元素

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) 元素。 |

**傳回值:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) 陣列