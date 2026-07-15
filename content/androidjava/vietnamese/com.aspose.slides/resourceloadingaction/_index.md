---
title: ResourceLoadingAction
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định chế độ tải tài nguyên bên ngoài.
type: docs
url: /vi/com.aspose.slides/resourceloadingaction/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Xác định chế độ tải tài nguyên bên ngoài.
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | Aspose.Slides sẽ tải tài nguyên bên ngoài như bình thường. |
| [Skip](#Skip) | Aspose.Slides sẽ bỏ qua việc tải tài nguyên bên ngoài. |
| [UserProvided](#UserProvided) | Aspose.Slides sẽ sử dụng mảng byte được người dùng cung cấp trong [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) làm dữ liệu hình ảnh. |
### Mặc định {#Default}
```
public static final int Default
```

Aspose.Slides sẽ tải tài nguyên bên ngoài như bình thường.

### Bỏ qua {#Skip}
```
public static final int Skip
```

Aspose.Slides sẽ bỏ qua việc tải tài nguyên bên ngoài. Chỉ liên kết không có dữ liệu sẽ được lưu cho hình ảnh.

### Cung cấp bởi người dùng {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides sẽ sử dụng mảng byte được người dùng cung cấp trong [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) làm dữ liệu hình ảnh.