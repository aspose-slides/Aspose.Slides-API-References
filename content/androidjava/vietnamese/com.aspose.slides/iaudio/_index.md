---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho một tệp âm thanh được nhúng.
type: docs
url: /vi/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Đại diện cho một tệp âm thanh được nhúng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContentType()](#getContentType--) | Trả về kiểu MIME của một âm thanh, được mã hoá trong (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao của dữ liệu âm thanh. |
| [getStream()](#getStream--) | Trả về luồng Stream để đọc. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Trả về kiểu MIME của một âm thanh, được mã hoá trong (\#getBinaryData.getBinaryData). Chỉ đọc String.

**Trả về:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Trả về bản sao của dữ liệu âm thanh. Trong trường hợp dữ liệu lớn, cân nhắc sử dụng phương thức \#getStream.getStream để ngăn việc tải dữ liệu âm thanh không cần thiết vào bộ nhớ hoặc thậm chí gây OutOfMemoryException. Chỉ đọc byte[].

**Trả về:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Trả về luồng Stream để đọc. Sử dụng 'using' hoặc đóng luồng sau khi dùng.

**Trả về:**
java.io.InputStream - Luồng để đọc.