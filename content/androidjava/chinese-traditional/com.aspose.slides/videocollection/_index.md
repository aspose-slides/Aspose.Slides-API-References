---
title: VideoCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 Video 物件的集合。
type: docs
url: /zh-hant/com.aspose.slides/videocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

表示 Video 物件的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 返回集合中影片檔案的數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 從另一個簡報新增影片檔案的副本。 |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | 從串流建立並將影片新增至簡報。 |
| [addVideo(byte[] videoData)](#addVideo-byte---) | 從位元組陣列建立並將影片新增至簡報。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 從指定索引開始將影片複製到指定陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回指示對集合的存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
### size() {#size--}
```
public final int size()
```


返回集合中影片檔案的數量。 唯讀 int。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


取得指定索引處的元素。 唯讀 [IVideo](../../com.aspose.slides/ivideo)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```


從另一個簡報新增影片檔案的副本。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | 來源影片。 |

**返回：**
[IVideo](../../com.aspose.slides/ivideo) - 已新增影片。
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


從串流建立並將影片新增至簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 要從其加入影片檔案的串流。 |
| loadingStreamBehavior | int | 將套用於串流的行為。 |

**返回：**
[IVideo](../../com.aspose.slides/ivideo) - 已新增 [IVideo](../../com.aspose.slides/ivideo)。
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


從位元組陣列建立並將影片新增至簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| videoData | byte[] | 影片位元組。 |

**返回：**
[IVideo](../../com.aspose.slides/ivideo) - 已新增影片。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


從指定索引開始將影片複製到指定陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 陣列。 |
| index | int | 索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


返回指示對集合的存取是否同步（執行緒安全）的值。 唯讀 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


返回同步根。 唯讀 Object。

**返回：**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


返回可遍歷集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


返回整個集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - 用於整個集合的 java.util.Iterator。