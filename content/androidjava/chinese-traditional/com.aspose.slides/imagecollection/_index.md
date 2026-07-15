---
title: ImageCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 PPImage 的集合。
type: docs
url: /zh-hant/com.aspose.slides/imagecollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有實作的介面：**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

表示 PPImage 的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 傳回集合中圖像的數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 從另一個簡報加入圖像的副本。 |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | 將圖像加入簡報。 |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | 從串流將圖像加入簡報。 |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | 從串流建立並將圖像加入簡報。 |
| [addImage(byte[] buffer)](#addImage-byte---) | 從指定的緩衝區將圖像加入簡報。 |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | 從 Svg 物件將圖像加入簡報。 |
| [iterator()](#iterator--) | 傳回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示對集合的存取是否已同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### size() {#size--}
```
public final int size()
```


傳回集合中圖像的數量。唯讀 int 。

**傳回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


取得指定索引處的元素。唯讀 [IPPImage](../../com.aspose.slides/ippimage)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


從另一個簡報加入圖像的副本。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | 來源圖像。 |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的圖像。
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


將圖像加入簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 要加入的圖像。 |

--------------------

此方法會在將 WMF/EMF 中繪圖檔轉換為點陣 PNG 圖像後，插入至簡報。 |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的圖像。
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


從串流將圖像加入簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 從此串流加入圖像。 |

--------------------

此方法可在不將 WMF/EMF 中繪圖檔轉換為點陣 PNG 圖像的情況下，直接加入簡報。 |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的圖像。
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


從串流建立並將圖像加入簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 從此串流加入圖像檔案。 |
| loadingStreamBehavior | int | 將套用於串流的行為。 |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入 [IPPImage](../../com.aspose.slides/ippimage)。
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


從指定的緩衝區將圖像加入簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | byte[] | 緩衝區。 |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的圖像。
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


從 Svg 物件將圖像加入簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg 圖像物件 [ISvgImage](../../com.aspose.slides/isvgimage) |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的圖像。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


傳回遍歷集合的列舉器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


傳回整個集合的 java 迭代器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


傳回指示對集合的存取是否已同步（執行緒安全）的值。唯讀 boolean 。

**傳回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


傳回同步根。唯讀 Object 。

**傳回值：**
java.lang.Object