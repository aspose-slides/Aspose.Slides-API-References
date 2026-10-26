---
title: IAudioCollection
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示一個嵌入式音訊檔案的集合。
type: docs
url: /zh-hant/com.aspose.slides/iaudiocollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

表示一個嵌入式音訊檔案的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | 從另一個簡報加入音訊檔案的副本。 |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | 從串流建立並加入音訊至簡報。 |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | 從串流建立並加入音訊至簡報。 |
| [addAudio(byte[] audioData)](#addAudio-byte---) | 從位元組陣列建立並加入音訊至簡報。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

取得指定索引處的元素。唯讀 [IAudio](../../com.aspose.slides/iaudio)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IAudio](../../com.aspose.slides/iaudio)

### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

從另一個簡報加入音訊檔案的副本。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 來源音訊。 |

**傳回值：**
[IAudio](../../com.aspose.slides/iaudio) - 已加入的音訊。

### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

從串流建立並加入音訊至簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 要加入音訊的串流。 |

**傳回值：**
[IAudio](../../com.aspose.slides/iaudio) - 已加入的音訊。

### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

從串流建立並加入音訊至簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 要加入視訊音訊的串流。 |
| loadingStreamBehavior | int | 將套用於串流的 [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior)。 |

**傳回值：**
[IAudio](../../com.aspose.slides/iaudio) - 已加入的音訊。

### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

從位元組陣列建立並加入音訊至簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| audioData | byte[] | 音訊位元組。 |

**傳回值：**
[IAudio](../../com.aspose.slides/iaudio) - 已加入的音訊。