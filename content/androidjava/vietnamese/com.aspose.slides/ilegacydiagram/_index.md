---
title: ILegacyDiagram
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một đối tượng sơ đồ kế thừa
type: docs
url: /vi/com.aspose.slides/ilegacydiagram/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Biểu diễn một đối tượng sơ đồ kế thừa
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Chuyển đổi sơ đồ legacy thành đối tượng SmartArt có thể chỉnh sửa. |
| [convertToGroupShape()](#convertToGroupShape--) | Chuyển đổi sơ đồ legacy thành nhóm hình có thể chỉnh sửa. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Chuyển đổi sơ đồ legacy thành đối tượng SmartArt có thể chỉnh sửa. Đối tượng SmartArt được tạo sẽ được thêm vào nhóm hình cha ở cùng vị trí.

**Trả về:**
[ISmartArt](../../com.aspose.slides/ismartart) - Đối tượng SmartArt đã tạo.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Chuyển đổi sơ đồ legacy thành nhóm hình có thể chỉnh sửa. Đối tượng GroupShape được tạo sẽ được thêm vào nhóm hình cha ở cùng vị trí.

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Đối tượng GroupShape đã tạo.