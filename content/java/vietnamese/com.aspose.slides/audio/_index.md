---
title: Audio
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một tệp âm thanh nhúng.
type: docs
url: /vi/com.aspose.slides/audio/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Đại diện cho một tệp âm thanh nhúng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getContentType()](#getContentType--) | Trả về MIME type của audio, được mã hoá trong (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Trả về MIME type của audio, được mã hoá trong (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Trả về bản sao dữ liệu của audio. |
| [getStream()](#getStream--) | Trả về Stream stream để đọc. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Trả về MIME type của audio, được mã hoá trong (\#getBinaryData.getBinaryData). String chỉ-đọc.

**Trả về:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Trả về MIME type của audio, được mã hoá trong (\#getBinaryData.getBinaryData). String chỉ-đọc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Trả về bản sao dữ liệu của audio. Trong trường hợp lượng dữ liệu lớn hãy cân nhắc sử dụng phương thức \#getStream.getStream để ngăn việc tải dữ liệu audio không cần thiết vào bộ nhớ hoặc thậm chí OutOfMemoryException. byte[] chỉ-đọc.

**Trả về:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Trả về Stream stream để đọc. Sử dụng 'using' hoặc đóng stream sau khi sử dụng.

**Trả về:**
java.io.InputStream - Stream để đọc.