---
title: ILayoutSlideCollection
second_title: Aspose.Slides for Java API 參考
description: 表示版面投影片集合的基礎類別。
type: docs
url: /zh-hant/com.aspose.slides/ilayoutslidecollection/
---
**已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

表示版面投影片集合的基礎類別。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據索引返回版面投影片。 |
| [getByType(byte type)](#getByType-byte-) | 返回指定類型的第一個版面投影片。 |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | 從集合中移除版面。 |
| [removeUnused()](#removeUnused--) | 移除未使用的版面投影片（HasDependingSlides 為 false 的版面投影片）。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


根據索引返回版面投影片。唯讀 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| index | int |  |

**回傳值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


返回指定類型的第一個版面投影片。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| type | byte | 要尋找的版面投影片類型。 |

**回傳值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) 具有指定類型的版面投影片，若未找到任何版面則返回 null。
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


從集合中移除版面。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要從集合中移除的版面投影片。

--------------------

1) 為避免拋出 PptxEditException，請先檢查版面的 HasDependingSlides 屬性。2) 也可以使用 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 方法來簡化程式碼。 |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


移除未使用的版面投影片（HasDependingSlides 為 false 的版面投影片）。