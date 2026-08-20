---
title: VideoCollection
second_title: Aspose.Slides for Java API 參考
description: 表示 Video 物件的集合。
type: docs
url: /zh-hant/com.aspose.slides/videocollection/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面:**  
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)  
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

表示 Video 物件的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 傳回集合中視訊檔案的數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 從其他簡報中添加視訊檔案的副本。 |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | 從串流建立並將視訊加入簡報。 |
| [addVideo(byte[] videoData)](#addVideo-byte---) | 建立並將視訊加入簡報（從位元組陣列）。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將視訊複製到指定的陣列，起始於指定的索引。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |

### size() {#size--}
```
public final int size()
```

傳回集合中視訊檔案的數量。唯讀 int.

**傳回:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

取得指定索引處的元素。唯讀 [IVideo](../../com.aspose.slides/ivideo)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回:**  
[IVideo](../../com.aspose.slides/ivideo)

### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

從其他簡報中添加視訊檔案的副本。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | 原始視訊。 |

**傳回:**  
[IVideo](../../com.aspose.slides/ivideo) - 已加入的視訊。

### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

從串流建立並將視訊加入簡報。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 用於加入視訊檔案的串流。 |
| loadingStreamBehavior | int | 將套用於串流的行為。 |

**傳回:**  
[IVideo](../../com.aspose.slides/ivideo) - 已加入 [IVideo](../../com.aspose.slides/ivideo)。

### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

從位元組陣列建立並將視訊加入簡報。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| videoData | byte[] | 視訊位元組。 |

**傳回:**  
[IVideo](../../com.aspose.slides/ivideo) - 已加入的視訊。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將視訊複製到指定的陣列，起始於指定的索引。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 陣列。 |
| index | int | 索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**傳回:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

傳回可遍歷集合的列舉器。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - 整個集合的 java.util.Iterator。