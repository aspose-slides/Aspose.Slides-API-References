---
title: CaptionsCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示闭合字幕的集合。
type: docs
url: /zh/com.aspose.slides/captionscollection/
---
**继承：**
java.lang.Object

**全部实现的接口：**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

表示闭合字幕的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的闭合字幕。 |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | 将 WebVTT 闭合字幕添加到集合的末尾。 |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | 从流中将 WebVTT 闭合字幕添加到集合的末尾。 |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | 从集合中移除指定的闭合字幕。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引处的闭合字幕。 |
| [clear()](#clear--) | 移除集合中的所有闭合字幕。 |
| [getCount()](#getCount--) | 返回集合中元素的数量。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

返回指定索引处的闭合字幕。只读 [ICaptions](../../com.aspose.slides/icaptions)。

**参数**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

将 WebVTT 闭合字幕添加到集合的末尾。

**参数**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | java.lang.String | 闭合字幕的标签。 |
| filePath | java.lang.String | WebVTT 文件的路径。 |

**返回：**
[ICaptions](../../com.aspose.slides/icaptions) - 添加的 [ICaptions](../../com.aspose.slides/icaptions) 实例。
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

从流中将 WebVTT 闭合字幕添加到集合的末尾。

**参数**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | java.lang.String | 闭合字幕的标签。 |
| stream | java.io.InputStream | 包含 WebVTT 格式数据的输入流。 |

**返回：**
[ICaptions](../../com.aspose.slides/icaptions) - 添加的 [ICaptions](../../com.aspose.slides/icaptions) 实例。
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

从集合中移除指定的闭合字幕。

**参数**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | 要移除的闭合字幕。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除指定索引处的闭合字幕。

**参数**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的闭合字幕的索引。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有闭合字幕。

### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中元素的数量。只读 int。

**返回：**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

返回一个遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - 可用于遍历集合的 System.Collections.Generic.IEnumerator1。