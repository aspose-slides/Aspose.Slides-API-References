---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn thông tin dữ liệu nhúng cho đối tượng OLE.
type: docs
url: /vi/com.aspose.slides/oleembeddeddatainfo/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Biểu diễn thông tin dữ liệu nhúng cho đối tượng OLE.

## Phương thức khởi tạo

| Phương thức khởi tạo | Mô tả |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Creates new embedded data info for OLE object. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Creates a new instance of an embedded data info for OLE object. |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Returns the file data of an embedded OLE object Read only byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Returns the file extension for the current embedded OLE object Read only String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Tạo thông tin dữ liệu nhúng mới cho đối tượng OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Tạo một thể hiện mới của thông tin dữ liệu nhúng cho đối tượng OLE.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| embeddedFileData | byte[] | Dữ liệu tệp của một đối tượng OLE được nhúng byte[]. |
| embeddedFileExtension | java.lang.String | Phần mở rộng tệp cho đối tượng OLE nhúng hiện tại String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Trả về dữ liệu tệp của một đối tượng OLE được nhúng Chỉ đọc byte[].

**Trả về:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Trả về phần mở rộng tệp cho đối tượng OLE nhúng hiện tại Chỉ đọc String.

**Trả về:**
java.lang.String