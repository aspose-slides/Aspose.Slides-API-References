---
title: ILegacyDiagram
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل كائن مخطط قديم
type: docs
url: /ar/com.aspose.slides/ilegacydiagram/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

يمثل كائن مخطط قديم
## الطرق

| طريقة | الوصف |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | يحوّل المخطط القديم إلى كائن SmartArt قابل للتحرير. |
| [convertToGroupShape()](#convertToGroupShape--) | يحوّل المخطط القديم إلى شكل مجموعة قابل للتحرير. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

يحوّل المخطط القديم إلى كائن SmartArt قابل للتحرير. يضيف كائن SmartArt المنشأ إلى شكل المجموعة الأصل في نفس الموقع.

**الإرجاع:**
[ISmartArt](../../com.aspose.slides/ismartart) - كائن SmartArt المنشأ.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

يحوّل المخطط القديم إلى شكل مجموعة قابل للتحرير. يضيف كائن GroupShape المنشأ إلى شكل المجموعة الأصل في نفس الموقع.

**الإرجاع:**
[IGroupShape](../../com.aspose.slides/igroupshape) - كائن GroupShape المنشأ.