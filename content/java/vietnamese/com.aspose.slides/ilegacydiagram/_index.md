---
title: ILegacyDiagram
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một đối tượng sơ đồ legacy
type: docs
url: /vi/com.aspose.slides/ilegacydiagram/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Biểu diễn một đối tượng sơ đồ legacy
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Chuyển đổi sơ đồ legacy sang đối tượng SmartArt có thể chỉnh sửa. |
| [convertToGroupShape()](#convertToGroupShape--) | Chuyển đổi sơ đồ legacy sang group shape có thể chỉnh sửa. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Chuyển đổi sơ đồ legacy sang đối tượng SmartArt có thể chỉnh sửa. Đối tượng SmartArt được tạo sẽ được thêm vào group shape cha ở cùng vị trí.

**Trả về:**
[ISmartArt](../../com.aspose.slides/ismartart) - Đối tượng SmartArt được tạo.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Chuyển đổi sơ đồ legacy sang group shape có thể chỉnh sửa. Đối tượng GroupShape được tạo sẽ được thêm vào group shape cha ở cùng vị trí.

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Đối tượng GroupShape được tạo.