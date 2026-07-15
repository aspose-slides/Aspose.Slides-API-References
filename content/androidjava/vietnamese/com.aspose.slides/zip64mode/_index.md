---
title: Zip64Mode
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định thời điểm sử dụng phần mở rộng định dạng ZIP64 cho tệp OpenXML.
type: docs
url: /vi/com.aspose.slides/zip64mode/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Xác định thời điểm sử dụng phần mở rộng định dạng ZIP64 cho tệp OpenXML.

--------------------

Tệp OpenXML là một tệp ZIP có giới hạn 4 GB (2^32 byte) cho kích thước chưa nén của một tệp, kích thước đã nén của một tệp và tổng kích thước của kho lưu trữ, đồng thời có giới hạn 65.535 (2^16-1) tệp trong kho lưu trữ. Các phần mở rộng định dạng ZIP64 tăng các giới hạn lên đến 2^64.
## Các trường

| Trường | Mô tả |
| --- | --- |
| [Never](#Never) | Không sử dụng phần mở rộng ZIP64. |
| [IfNecessary](#IfNecessary) | Sử dụng phần mở rộng ZIP64 nếu cần thiết. |
| [Always](#Always) | Luôn sử dụng phần mở rộng ZIP64. |
### Never {#Never}
```
public static final int Never
```


Không sử dụng phần mở rộng ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


Sử dụng phần mở rộng ZIP64 nếu cần thiết.

### Always {#Always}
```
public static final int Always
```


Luôn sử dụng phần mở rộng ZIP64.