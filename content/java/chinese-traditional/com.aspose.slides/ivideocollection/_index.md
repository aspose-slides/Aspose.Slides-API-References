---
title: IVideoCollection
second_title: Aspose.Slides for Java API 參考
description: 表示 Video 物件的集合。
type: docs
url: /zh-hant/com.aspose.slides/ivideocollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

表示 Video 物件的集合。
## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 從其他簡報中加入視訊檔案的副本。 |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | 從串流建立並將視訊加入簡報。 |
| [addVideo(byte[] videoData)](#addVideo-byte---) | 從位元組陣列建立並將視訊加入簡報。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


取得指定索引處的元素。唯讀 [IVideo](../../com.aspose.slides/ivideo)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


從其他簡報中加入視訊檔案的副本。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | 來源視訊。 |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo) - 已加入的視訊。
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


從串流建立並將視訊加入簡報。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | 用於加入視訊檔案的串流。 |
| loadingStreamBehavior | int | 將套用於串流的行為。 |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo) - 已加入的 [IVideo](../../com.aspose.slides/ivideo)。
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


從位元組陣列建立並將視訊加入簡報。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| videoData | byte[] | 視訊位元組。 |

**Returns:**
[IVideo](../../com.aspose.slides/ivideo) - 已加入的視訊。