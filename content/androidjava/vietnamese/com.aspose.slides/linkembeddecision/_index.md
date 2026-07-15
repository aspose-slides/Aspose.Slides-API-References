---
title: LinkEmbedDecision
second_title: Tham chiếu API Java cho Aspose.Slides cho Android
description: Xác định cách đối tượng sẽ được xử lý khi lưu.
type: docs
url: /vi/com.aspose.slides/linkembeddecision/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Xác định cách đối tượng sẽ được xử lý khi lưu.
## Trường

| Trường | Mô tả |
| --- | --- |
| [Link](#Link) | Đối tượng sẽ được lưu trữ bên ngoài, được tham chiếu bằng URL |
| [Embed](#Embed) | Đối tượng nên được nhúng vào tệp được tạo nếu có thể. |
| [Ignore](#Ignore) | Đối tượng sẽ bị bỏ qua. |
### Liên kết {#Link}
```
public static final int Link
```

Đối tượng sẽ được lưu trữ bên ngoài, được tham chiếu bằng URL

### Nhúng {#Embed}
```
public static final int Embed
```

Đối tượng nên được nhúng vào tệp được tạo nếu có thể. Nếu việc nhúng không khả thi, GetUrl sẽ được gọi và, tùy thuộc vào kết quả, đối tượng sẽ được tham chiếu bằng URL hoặc bị bỏ qua.

### Bỏ qua {#Ignore}
```
public static final int Ignore
```

Đối tượng sẽ bị bỏ qua.