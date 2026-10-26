---
title: Audio
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho một tệp âm thanh nhúng.
type: docs
url: /vi/com.aspose.slides/audio/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Đại diện cho một tệp âm thanh nhúng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContentType()](#getContentType--) | Trả về một kiểu MIME của âm thanh, được mã hoá trong (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Trả về một kiểu MIME của âm thanh, được mã hoá trong (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao dữ liệu của âm thanh. |
| [getStream()](#getStream--) | Trả về luồng Stream để đọc. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Trả về một kiểu MIME của âm thanh, được mã hoá trong (\#getBinaryData.getBinaryData). String chỉ đọc.

**Trả về:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Trả về một kiểu MIME của âm thanh, được mã hoá trong (\#getBinaryData.getBinaryData). String chỉ đọc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Trả về bản sao dữ liệu của âm thanh. Trong trường hợp dữ liệu lớn, xem xét sử dụng phương thức \#getStream.getStream để tránh việc tải dữ liệu âm thanh không cần thiết vào bộ nhớ hoặc thậm chí gây ra OutOfMemoryException. byte[] chỉ đọc.

**Trả về:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Trả về luồng Stream để đọc. Sử dụng 'using' hoặc đóng luồng sau khi dùng.

**Trả về:**
java.io.InputStream - Luồng để đọc.