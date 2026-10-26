---
title: LegacyDiagram
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một đối tượng sơ đồ kế thừa.
type: docs
url: /vi/com.aspose.slides/legacydiagram/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Biểu diễn một đối tượng sơ đồ kế thừa.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Chuyển đổi legacy digram sang đối tượng SmartArt có thể chỉnh sửa. |
| [convertToGroupShape()](#convertToGroupShape--) | Chuyển đổi legacy digram sang shape nhóm có thể chỉnh sửa. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


Chuyển đổi legacy digram sang đối tượng SmartArt có thể chỉnh sửa. Đối tượng SmartArt được tạo sẽ được thêm vào parent group shape ở cùng vị trí.

**Trả về:**
[ISmartArt](../../com.aspose.slides/ismartart) - Đối tượng SmartArt được tạo.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


Chuyển đổi legacy digram sang shape nhóm có thể chỉnh sửa. Đối tượng GroupShape được tạo sẽ được thêm vào parent group shape ở cùng vị trí.

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Đối tượng GroupShape được tạo.