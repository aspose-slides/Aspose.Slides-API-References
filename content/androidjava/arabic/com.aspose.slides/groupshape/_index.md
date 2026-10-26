---
title: GroupShape
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الأشكال على الشريحة.
type: docs
url: /ar/com.aspose.slides/groupshape/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

يمثل مجموعة من الأشكال على الشريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. |
| [getGroupShapeLock()](#getGroupShapeLock--) | يرجع أقفال الشكل. |
| [getShapes()](#getShapes--) | يرجع مجموعة الأشكال داخل المجموعة. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: يرجع null لكائنات GroupShape لأنها لا تملك خصائص خط. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


يرجع أقفال الشكل. قراءة فقط [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**الإرجاع:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


يرجع مجموعة الأشكال داخل المجموعة. قراءة فقط [IShapeCollection](../../com.aspose.slides/ishapecollection).

**الإرجاع:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)