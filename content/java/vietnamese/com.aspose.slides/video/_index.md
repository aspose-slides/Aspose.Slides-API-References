---
title: Video
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một hình ảnh được nhúng vào bản trình bày.
type: docs
url: /vi/com.aspose.slides/video/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Đại diện cho một hình ảnh được nhúng vào bản trình bày.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContentType()](#getContentType--) | Trả về kiểu MIME của một video, được mã hoá trong (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao dữ liệu của một âm thanh. |
| [getStream()](#getStream--) | Trả về luồng Stream để đọc. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Trả về kiểu MIME của một video, được mã hoá trong (\#getBinaryData.getBinaryData). Chuỗi chỉ đọc.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Trả về bản sao dữ liệu của một âm thanh. Trong trường hợp dữ liệu lớn, hãy xem xét việc sử dụng \#getStream.getStream method để ngăn việc tải dữ liệu video không cần thiết vào bộ nhớ hoặc thậm chí gây ra OutOfMemoryException. byte[] chỉ đọc.

**Returns:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Trả về luồng Stream để đọc. Sử dụng 'using' hoặc đóng luồng sau khi sử dụng.

**Returns:**
java.io.InputStream - Luồng để đọc.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent\_Immediate. IDOMObject chỉ đọc.

**Returns:**
com.aspose.slides.IDOMObject