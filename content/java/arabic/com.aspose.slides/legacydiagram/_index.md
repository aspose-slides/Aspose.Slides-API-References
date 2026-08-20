---
title: LegacyDiagram
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل كائن رسم بياني قديم.
type: docs
url: /ar/com.aspose.slides/legacydiagram/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

يمثل كائن رسم بياني قديم.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | يحول الرسم البياني القديم إلى كائن SmartArt قابل للتحرير. |
| [convertToGroupShape()](#convertToGroupShape--) | يحول الرسم البياني القديم إلى شكل مجموعة قابل للتحرير. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


يقوم بتحويل الرسم البياني القديم إلى كائن SmartArt قابل للتحرير. يتم إضافة كائن SmartArt الذي تم إنشاؤه إلى شكل المجموعة الأصلي في نفس الموقع.

**الإرجاع:**
[ISmartArt](../../com.aspose.slides/ismartart) - كائن SmartArt الذي تم إنشاؤه.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


يقوم بتحويل الرسم البياني القديم إلى شكل مجموعة قابل للتحرير. يتم إضافة كائن GroupShape الذي تم إنشاؤه إلى شكل المجموعة الأصلي في نفس الموقع.

**الإرجاع:**
[IGroupShape](../../com.aspose.slides/igroupshape) - كائن GroupShape الذي تم إنشاؤه.