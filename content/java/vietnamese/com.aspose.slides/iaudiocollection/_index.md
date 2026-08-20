---
title: IAudioCollection
second_title: Tham khảo API Aspose.Slides cho Java
description: Đại diện cho một bộ sưu tập các tệp âm thanh được nhúng.
type: docs
url: /vi/com.aspose.slides/iaudiocollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Mô tả một bộ sưu tập các tệp âm thanh được nhúng.
## Phương thức

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Thêm một bản sao của tệp âm thanh từ một bản trình chiếu khác. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Tạo và thêm một âm thanh vào bản trình chiếu từ luồng. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Tạo và thêm một âm thanh vào bản trình chiếu từ luồng. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Tạo và thêm một âm thanh vào bản trình chiếu từ mảng byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [IAudio](../../com.aspose.slides/iaudio).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Kết quả:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


Thêm một bản sao của tệp âm thanh từ một bản trình chiếu khác.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Âm thanh nguồn. |

**Kết quả:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã được thêm.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```


Tạo và thêm một âm thanh vào bản trình chiếu từ luồng.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm âm thanh. |

**Kết quả:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã được thêm.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Tạo và thêm một âm thanh vào bản trình chiếu từ luồng.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm âm thanh video. |
| loadingStreamBehavior | int | Giá trị [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) sẽ được áp dụng cho luồng. |

**Kết quả:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã được thêm.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


Tạo và thêm một âm thanh vào bản trình chiếu từ mảng byte.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Các byte âm thanh. |

**Kết quả:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã được thêm.