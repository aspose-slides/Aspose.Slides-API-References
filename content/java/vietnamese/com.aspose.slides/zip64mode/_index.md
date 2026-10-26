---
title: Zip64Mode
second_title: Tham chiếu API Aspose.Slides cho Java
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

Tệp OpenXML là một ZIP-archive có giới hạn 4 GB (2^32 byte) về kích thước không nén của một tệp, kích thước nén của một tệp và tổng kích thước của kho lưu trữ, cũng như giới hạn 65 535 (2^16-1) tệp trong kho lưu trữ. Các phần mở rộng định dạng ZIP64 tăng giới hạn lên 2^64.
## Các trường

| Field | Description |
| --- | --- |
| [Never](#Never) | Không sử dụng phần mở rộng định dạng ZIP64. |
| [IfNecessary](#IfNecessary) | Sử dụng phần mở rộng định dạng ZIP64 nếu cần. |
| [Always](#Always) | Luôn luôn sử dụng phần mở rộng định dạng ZIP64. |
### Never {#Never}
```
public static final int Never
```

Không sử dụng phần mở rộng định dạng ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Sử dụng phần mở rộng định dạng ZIP64 nếu cần.

### Always {#Always}
```
public static final int Always
```

Luôn luôn sử dụng phần mở rộng định dạng ZIP64.