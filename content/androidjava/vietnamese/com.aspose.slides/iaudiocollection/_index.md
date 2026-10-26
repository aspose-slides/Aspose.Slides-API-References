---
title: IAudioCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một tập hợp các tệp âm thanh đã nhúng.
type: docs
url: /vi/com.aspose.slides/iaudiocollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Biểu diễn một tập hợp các tệp âm thanh nhúng.
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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

Thêm một bản sao của tệp âm thanh từ một bản trình chiếu khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Âm thanh nguồn. |

**Giá trị trả về:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã thêm.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

Tạo và thêm một âm thanh vào bản trình chiếu từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm âm thanh. |

**Giá trị trả về:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã thêm.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Tạo và thêm một âm thanh vào bản trình chiếu từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm âm thanh. |
| loadingStreamBehavior | int | [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) sẽ được áp dụng cho luồng. |

**Giá trị trả về:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã thêm.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Tạo và thêm một âm thanh vào bản trình chiếu từ mảng byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| audioData | byte[] | Byte âm thanh. |

**Giá trị trả về:**
[IAudio](../../com.aspose.slides/iaudio) - Âm thanh đã thêm.