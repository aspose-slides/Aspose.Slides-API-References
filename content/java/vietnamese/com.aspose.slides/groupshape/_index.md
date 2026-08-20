---
title: GroupShape
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một nhóm các hình trên một slide.
type: docs
url: /vi/com.aspose.slides/groupshape/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Đại diện cho một nhóm các hình trên một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Trả về các khóa của hình. |
| [getShapes()](#getShapes--) | Trả về bộ sưu tập các hình bên trong nhóm. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình. Lưu ý: Trả về null cho các đối tượng GroupShape vì chúng không có thuộc tính đường. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Trả về các khóa của hình. Chỉ đọc [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Trả về:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Trả về bộ sưu tập các hình bên trong nhóm. Chỉ đọc [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Trả về:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)