---
title: ITabCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 Tab 的集合。
type: docs
url: /zh-hant/com.aspose.slides/itabcollection/
---
**已實作的介面:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

表示一個定位點的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [add(double position, int align)](#add-double-int-) | 將 Tab 新增至集合中。 |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | 將 Tab 新增至集合中。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


取得指定索引處的元素。唯讀 [ITab](../../com.aspose.slides/itab)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


將 Tab 新增至集合中。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | double | Tab 位置。 |
| align | int | Tab 對齊方式。 |

**傳回值:**
[ITab](../../com.aspose.slides/itab) - 已新增的 Tab。
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


將 Tab 新增至集合中。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | 要在集合末端加入的 Tab 物件。 |

**傳回值:**
int - Tab 被加入的索引位置。
### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有元素。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除集合中指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |