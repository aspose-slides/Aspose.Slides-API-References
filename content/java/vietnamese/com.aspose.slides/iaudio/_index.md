---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /vi/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Biểu diễn một tệp âm thanh được nhúng.
## Methods

| Phương thức | Mô tả |
| --- | --- |
| [getContentType()](#getContentType--) | Trả về kiểu MIME của một âm thanh, được mã hoá trong (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao dữ liệu của âm thanh. |
| [getStream()](#getStream--) | Trả về luồng Stream để đọc. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Trả về kiểu MIME của một âm thanh, được mã hoá trong (\#getBinaryData.getBinaryData). String chỉ đọc.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Trả về bản sao dữ liệu của âm thanh. Trong trường hợp lượng dữ liệu lớn, cân nhắc sử dụng phương thức \#getStream.getStream để tránh tải dữ liệu âm thanh không cần thiết vào bộ nhớ hoặc thậm chí gây OutOfMemoryException. byte[] chỉ đọc.

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Trả về luồng Stream để đọc. Sử dụng 'using' hoặc đóng luồng sau khi sử dụng.

**Returns:**
java.io.InputStream - Luồng để đọc.