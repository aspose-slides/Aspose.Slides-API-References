---
title: CaptionsCollection
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示隱藏式字幕的集合。
type: docs
url: /zh-hant/com.aspose.slides/captionscollection/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

表示隱藏式字幕的集合。
## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的隱藏式字幕。 |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | 將 WebVTT 隱藏式字幕新增至集合的末尾。 |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | 從串流將 WebVTT 隱藏式字幕新增至集合的末尾。 |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | 從集合中移除指定的隱藏式字幕。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的隱藏式字幕。 |
| [clear()](#clear--) | 從集合中移除所有隱藏式字幕。 |
| [getCount()](#getCount--) | 返回集合中元素的數量。 |
| [iterator()](#iterator--) | 返回一個可遍歷集合的列舉器。 |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

返回指定索引處的隱藏式字幕。唯讀 [ICaptions](../../com.aspose.slides/icaptions)。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

將 WebVTT 隱藏式字幕新增至集合的末尾。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| label | java.lang.String | 隱藏式字幕的標籤。 |
| filePath | java.lang.String | WebVTT 檔案的路徑。 |

**返回值：**
[ICaptions](../../com.aspose.slides/icaptions) - 已新增的 [ICaptions](../../com.aspose.slides/icaptions) 實例。
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

從串流將 WebVTT 隱藏式字幕新增至集合的末尾。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| label | java.lang.String | 隱藏式字幕的標籤。 |
| stream | java.io.InputStream | 包含 WebVTT 格式資料的輸入串流。 |

**返回值：**
[ICaptions](../../com.aspose.slides/icaptions) - 已新增的 [ICaptions](../../com.aspose.slides/icaptions) 實例。
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

從集合中移除指定的隱藏式字幕。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | 要移除的隱藏式字幕。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除指定索引處的隱藏式字幕。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除的隱藏式字幕的索引。 |

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有隱藏式字幕。

### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中元素的數量。唯讀 int 。

**返回值：**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

返回一個可遍歷集合的列舉器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - 一個可用於遍歷集合的 System.Collections.Generic.IEnumerator1。