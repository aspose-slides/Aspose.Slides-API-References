---
title: AudioCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho một bộ sưu tập các tệp âm thanh được nhúng.
type: docs
url: /vi/com.aspose.slides/audiocollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Đại diện cho một bộ sưu tập các tệp âm thanh được nhúng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng tệp âm thanh trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ số đã chỉ định. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Thêm một bản sao của tệp âm thanh từ một bài thuyết trình khác. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Tạo và thêm một âm thanh vào bài thuyết trình từ luồng. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Tạo và thêm một âm thanh vào bài thuyết trình từ luồng. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Tạo và thêm một âm thanh vào bài thuyết trình từ mảng byte. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép các âm thanh vào mảng đã chỉ định bắt đầu từ chỉ số đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
### size() {#size--}
```
public final int size()
```

Trả về số lượng tệp âm thanh trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Lấy phần tử tại chỉ số đã chỉ định. Chỉ đọc [IAudio](../../com.aspose.slides/iaudio).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Thêm một bản sao của tệp âm thanh từ một bài thuyết trình khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Âm thanh nguồn. |

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã thêm.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Tạo và thêm một âm thanh vào bài thuyết trình từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm âm thanh từ. |

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã thêm.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Tạo và thêm một âm thanh vào bài thuyết trình từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm video audio từ. |
| loadingStreamBehavior | int | Hành vi sẽ được áp dụng cho luồng. |

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã thêm.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Tạo và thêm một âm thanh vào bài thuyết trình từ mảng byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| audioData | byte[] | Các byte âm thanh. |

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã thêm.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép các âm thanh vào mảng đã chỉ định bắt đầu từ chỉ số đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng. |
| index | int | Chỉ số. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về gốc đồng bộ. Chỉ đọc Object.

**Trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - An java.util.Iterator for the entire collection.