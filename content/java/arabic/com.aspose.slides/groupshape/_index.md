---
title: GroupShape
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من الأشكال على شريحة.
type: docs
url: /ar/com.aspose.slides/groupshape/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

يمثّل مجموعة من الأشكال على شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. |
| [getGroupShapeLock()](#getGroupShapeLock--) | إرجاع أقفال الشكل. |
| [getShapes()](#getShapes--) | إرجاع مجموعة الأشكال داخل المجموعة. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: إرجاع null لكائنات GroupShape لأنها لا تملك خصائص الخط. للقراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

إرجاع أقفال الشكل. للقراءة فقط [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**الإرجاع:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

إرجاع مجموعة الأشكال داخل المجموعة. للقراءة فقط [IShapeCollection](../../com.aspose.slides/ishapecollection).

**الإرجاع:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)