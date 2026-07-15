---
title: IVideoCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 Video 物件的集合。
type: docs
url: /zh-hant/com.aspose.slides/ivideocollection/
---
**已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

表示 Video 物件的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引位置的元素。 |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 從另一個簡報中新增影片檔案的副本。 |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | 從串流建立並新增影片至簡報。 |
| [addVideo(byte[] videoData)](#addVideo-byte---) | 從位元組陣列建立並新增影片至簡報。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


取得指定索引位置的元素。唯讀 [IVideo](../../com.aspose.slides/ivideo)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


從另一個簡報中新增影片檔案的副本。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | 來源影片。 |

**傳回值：**
[IVideo](../../com.aspose.slides/ivideo) - 已新增的 video。
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


從串流建立並新增影片至簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 從其新增影片檔案的串流。 |
| loadingStreamBehavior | int | 將套用於串流的行為。 |

**傳回值：**
[IVideo](../../com.aspose.slides/ivideo) - 已新增的 [IVideo](../../com.aspose.slides/ivideo)。
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


從位元組陣列建立並新增影片至簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| videoData | byte[] | 影片位元組。 |

**傳回值：**
[IVideo](../../com.aspose.slides/ivideo) - 已新增的 video。