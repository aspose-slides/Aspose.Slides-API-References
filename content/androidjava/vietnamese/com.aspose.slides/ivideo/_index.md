---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho video được nhúng vào bài thuyết trình.
type: docs
url: /vi/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Đại diện cho video được nhúng vào bài thuyết trình.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContentType()](#getContentType--) | Trả về loại MIME của một video, được mã hoá trong (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao dữ liệu của một âm thanh. |
| [getStream()](#getStream--) | Trả về luồng Stream để đọc. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Trả về loại MIME của một video, được mã hoá trong (\#getBinaryData.getBinaryData). String chỉ đọc.

**Trả về:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Trả về bản sao dữ liệu của một âm thanh. Trong trường hợp lượng dữ liệu lớn, hãy cân nhắc sử dụng phương thức \#getStream.getStream để ngăn việc tải dữ liệu video không cần thiết vào bộ nhớ hoặc thậm chí gây ra OutOfMemoryException. byte[] chỉ đọc.

**Trả về:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Trả về luồng Stream để đọc. Sử dụng 'using' hoặc đóng luồng sau khi sử dụng.

**Trả về:**
java.io.InputStream - Luồng để đọc.