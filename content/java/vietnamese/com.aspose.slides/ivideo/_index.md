---
title: IVideo
second_title: Aspose.Slides for Java Tham chiếu API
description: Biểu diễn một video được nhúng vào bản trình bày.
type: docs
url: /vi/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Biểu diễn một video được nhúng vào bản trình bày.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContentType()](#getContentType--) | Trả về kiểu MIME của một video, được mã hoá trong (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao của dữ liệu âm thanh. |
| [getStream()](#getStream--) | Trả về Stream để đọc. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Trả về kiểu MIME của một video, được mã hoá trong (\#getBinaryData.getBinaryData). Chuỗi chỉ đọc.

**Giá trị trả về:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Trả về bản sao của dữ liệu âm thanh. Trong trường hợp dữ liệu lớn, hãy cân nhắc sử dụng \#getStream.getStream method để ngăn việc tải dữ liệu video không cần thiết vào bộ nhớ hoặc thậm chí gây OutOfMemoryException. Chỉ đọc byte[].

**Giá trị trả về:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Trả về Stream để đọc. Sử dụng 'using' hoặc đóng stream sau khi dùng.

**Giá trị trả về:**
java.io.InputStream - Stream để đọc.