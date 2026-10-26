---
title: ICaptionsCollection
second_title: Aspose.Slides Java API参考
description: 表示闭合字幕的集合。
type: docs
url: /zh/com.aspose.slides/icaptionscollection/
---
**所有实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

表示闭合字幕的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的闭合字幕。 |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | 将 WebVTT 闭合字幕添加到集合的末尾。 |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | 将 WebVTT 闭合字幕从流添加到集合的末尾。 |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | 从集合中删除指定的闭合字幕。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的闭合字幕。 |
| [clear()](#clear--) | 从集合中删除所有闭合字幕。 |
| [getCount()](#getCount--) | 返回集合中元素的数量。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

返回指定索引处的闭合字幕。只读 [ICaptions](../../com.aspose.slides/icaptions)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```

将 WebVTT 闭合字幕添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | java.lang.String | 闭合字幕的标签。 |
| filePath | java.lang.String | WebVTT 文件的路径。 |

**返回：**
[ICaptions](../../com.aspose.slides/icaptions) - 添加的 [ICaptions](../../com.aspose.slides/icaptions) 实例。
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

将 WebVTT 闭合字幕从流添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | java.lang.String | 闭合字幕的标签。 |
| stream | java.io.InputStream | 包含 WebVTT 格式数据的输入流。 |

**返回：**
[ICaptions](../../com.aspose.slides/icaptions) - 添加的 [ICaptions](../../com.aspose.slides/icaptions) 实例。
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

从集合中删除指定的闭合字幕。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | 要删除的闭合字幕。 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除指定索引处的闭合字幕。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的闭合字幕的索引。 |
### clear() {#clear--}
```
public abstract void clear()
```

从集合中删除所有闭合字幕。
### getCount() {#getCount--}
```
public abstract int getCount()
```

返回集合中元素的数量。只读 int 。

**返回：**
int