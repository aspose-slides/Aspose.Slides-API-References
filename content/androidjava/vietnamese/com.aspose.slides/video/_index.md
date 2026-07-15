---
title: Video
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Mô tả một hình ảnh được nhúng vào bản trình chiếu.
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

Mô tả một hình ảnh được nhúng vào bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContentType()](#getContentType--) | Trả về một MIME type của video, được mã hoá trong (#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao của dữ liệu âm thanh. |
| [getStream()](#getStream--) | Trả về Stream stream để đọc. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Trả về một MIME type của video, được mã hoá trong (#getBinaryData.getBinaryData). Chỉ đọc String.

**Trả về:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Trả về bản sao của dữ liệu âm thanh. Trong trường hợp lượng dữ liệu lớn, nên sử dụng phương thức #getStream.getStream để ngăn việc tải dữ liệu video vào bộ nhớ một cách không cần thiết hoặc thậm chí gây OutOfMemoryException. Chỉ đọc byte[].

**Trả về:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Trả về Stream stream để đọc. Sử dụng 'using' hoặc đóng stream sau khi sử dụng.

**Trả về:**
java.io.InputStream - Stream để đọc.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject