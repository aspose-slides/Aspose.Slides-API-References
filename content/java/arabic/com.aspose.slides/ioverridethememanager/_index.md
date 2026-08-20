---
title: IOverrideThemeManager
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يوفر الوصول إلى أنواع مختلفة من السمات المتجاوزة.
type: docs
url: /ar/com.aspose.slides/ioverridethememanager/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

يوفر الوصول إلى أنواع مختلفة من السمات المتجاوزة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعالة الموروثة أم لا. |
| [getOverrideTheme()](#getOverrideTheme--) | يرجع كائن السمة المتجاوزة. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | يرجع كائن السمة المتجاوزة. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعالة الموروثة أم لا. لتمكين OverrideTheme من التجاوز، استخدم طرق OverrideTheme.Init*(). لتعطيل OverrideTheme من التجاوز، استخدم طريقة OverrideTheme.Clear(). منطقي للقراءة فقط.

**إرجاع:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

يرجع كائن السمة المتجاوزة. قابل للقراءة والكتابة [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**إرجاع:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

يرجع كائن السمة المتجاوزة. قابل للقراءة والكتابة [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |