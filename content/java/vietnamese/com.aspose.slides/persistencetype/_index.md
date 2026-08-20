---
title: PersistenceType
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định phương pháp được sử dụng để lưu trữ các thuộc tính của điều khiển ActiveX.
type: docs
url: /vi/com.aspose.slides/persistencetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

Specifies the method used to store properties of the ActiveX control.
## Fields

| Field | Description |
| --- | --- |
| [NotDefined](#NotDefined) | Id persistence không được chỉ định. |
| [PersistPropertyBag](#PersistPropertyBag) | Chỉ định rằng ActiveX control được lưu trữ bằng phương pháp persistence dựa trên property-bag. |
| [PersistStream](#PersistStream) | Chỉ định rằng ActiveX control được lưu trữ bằng phương pháp persistence dựa trên stream mà không hỗ trợ khởi tạo ActiveX control về trạng thái mặc định. |
| [PersistStreamInit](#PersistStreamInit) | Chỉ định rằng ActiveX control được lưu trữ bằng phương pháp persistence dựa trên stream hỗ trợ khởi tạo ActiveX control về trạng thái mặc định. |
| [PersistStorage](#PersistStorage) | Chỉ định rằng ActiveX control được lưu trữ bằng phương pháp persistence dựa trên storage. |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```

Id persistence không được chỉ định.

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

Chỉ định rằng ActiveX control được lưu trữ bằng phương pháp persistence dựa trên property-bag. Property-bag-based persistence lưu một ActiveX control thông qua một tập hợp các cặp tên và giá trị mô tả dữ liệu được lưu trữ bởi ActiveX control.

### PersistStream {#PersistStream}
```
public static final int PersistStream
```

Chỉ định rằng ActiveX control được lưu trữ bằng phương pháp persistence dựa trên stream mà không hỗ trợ khởi tạo ActiveX control về trạng thái mặc định.

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

Chỉ định rằng ActiveX control được lưu trữ bằng phương pháp persistence dựa trên stream hỗ trợ khởi tạo ActiveX control về trạng thái mặc định.

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

Chỉ định rằng ActiveX control được lưu trữ bằng phương pháp persistence dựa trên storage.