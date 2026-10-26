---
title: ICaptionsCollection
second_title: Aspose.Slides for Java API 參考
description: 表示一個隱藏式字幕的集合。
type: docs
url: /zh-hant/com.aspose.slides/icaptionscollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

表示一個隱藏式字幕的集合。
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的隱藏式字幕。 |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | 將 WebVTT 隱藏式字幕加入集合的末端。 |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | 從串流將 WebVTT 隱藏式字幕加入集合的末端。 |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | 從集合中移除指定的隱藏式字幕。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的隱藏式字幕。 |
| [clear()](#clear--) | 從集合中移除所有隱藏式字幕。 |
| [getCount()](#getCount--) | 返回集合中元素的數量。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


返回指定索引處的隱藏式字幕。唯讀 [ICaptions](../../com.aspose.slides/icaptions)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


將 WebVTT 隱藏式字幕加入集合的末端。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | java.lang.String | 隱藏式字幕的標籤。 |
| filePath | java.lang.String | WebVTT 檔案的路徑。 |

**Returns:**
[ICaptions](../../com.aspose.slides/icaptions) - 已新增的 [ICaptions](../../com.aspose.slides/icaptions) 實例。
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


從串流將 WebVTT 隱藏式字幕加入集合的末端。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | java.lang.String | 隱藏式字幕的標籤。 |
| stream | java.io.InputStream | 包含 WebVTT 格式資料的輸入串流。 |

**Returns:**
[ICaptions](../../com.aspose.slides/icaptions) - 已新增的 [ICaptions](../../com.aspose.slides/icaptions) 實例。
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


從集合中移除指定的隱藏式字幕。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | 要移除的隱藏式字幕。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除指定索引處的隱藏式字幕。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除的隱藏式字幕的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有隱藏式字幕。

### getCount() {#getCount--}
```
public abstract int getCount()
```


返回集合中元素的數量。唯讀  int 。

**Returns:**
int