---
title: IPointCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一個部份的集合。
type: docs
url: /zh-hant/com.aspose.slides/ipointcollection/
---
**已實作的介面:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPointCollection extends System.Collections.Generic.IGenericEnumerable<IPoint>
```

表示一個部份的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 傳回集合中點的數量。 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的點。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```


傳回集合中點的數量。唯讀 int。

**傳回:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IPoint get_Item(int index)
```


傳回指定索引處的點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**傳回:**
[IPoint](../../com.aspose.slides/ipoint) - [IPoint](../../com.aspose.slides/ipoint) 物件。