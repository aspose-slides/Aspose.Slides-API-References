---
title: AudioCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一個嵌入式音訊檔案的集合。
type: docs
url: /zh-hant/com.aspose.slides/audiocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

表示一個嵌入式音訊檔案的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 傳回集合中音訊檔案的數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | 從另一個簡報加入音訊檔案的副本。 |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | 從串流建立並加入音訊到簡報。 |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | 從串流建立並加入音訊到簡報。 |
| [addAudio(byte[] audioData)](#addAudio-byte---) | 從位元組陣列建立並加入音訊到簡報。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將音訊複製到指定的陣列，從指定的索引開始。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 Java 迭代器。 |
### size() {#size--}
```
public final int size()
```

傳回集合中音訊檔案的數量。唯讀 int。

**傳回:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

取得指定索引處的元素。唯讀 [IAudio](../../com.aspose.slides/iaudio)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

從另一個簡報加入音訊檔案的副本。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 來源音訊。 |

**傳回:**
[IAudio](../../com.aspose.slides/iaudio) - 已加入的音訊。
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

從串流建立並加入音訊到簡報。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 用於加入音訊的串流。 |

**傳回:**
[IAudio](../../com.aspose.slides/iaudio) - 已加入的音訊。
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

從串流建立並加入音訊到簡報。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 用於加入視訊音訊的串流。 |
| loadingStreamBehavior | int | 將套用於串流的行為。 |

**傳回:**
[IAudio](../../com.aspose.slides/iaudio) - 已加入的音訊。
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

從位元組陣列建立並加入音訊到簡報。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| audioData | byte[] | 音訊位元組。 |

**傳回:**
[IAudio](../../com.aspose.slides/iaudio) - 已加入的音訊。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將音訊複製到指定的陣列，從指定的索引開始。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 陣列。 |
| index | int | 索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 boolean。

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
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

傳回可遍歷集合的列舉器。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - 一個可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

傳回整個集合的 java.util.Iterator。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - 整個集合的 java.util.Iterator。