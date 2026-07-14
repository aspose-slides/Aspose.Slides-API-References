---
title: ILegacyDiagram
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثّل كائن مخطط قديم
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

| الطريقة | الوصف |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | يحول مخططًا قديمًا إلى كائن SmartArt قابل للتحرير. |
| [convertToGroupShape()](#convertToGroupShape--) | يحول مخططًا قديمًا إلى شكل مجموعة قابل للتحرير. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

يحول مخططًا قديمًا إلى كائن SmartArt قابل للتحرير. يُضيف كائن SmartArt المُنشأ إلى شكل المجموعة الأصل في نفس الموقع.

**الإرجاع:**
[ISmartArt](../../com.aspose.slides/ismartart) - كائن SmartArt المُنشأ.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

يحول مخططًا قديمًا إلى شكل مجموعة قابل للتحرير. يُضيف كائن GroupShape المُنشأ إلى شكل المجموعة الأصل في نفس الموقع.

**الإرجاع:**
[IGroupShape](../../com.aspose.slides/igroupshape) - كائن GroupShape المُنشأ.