---
title: IOverrideThemeManager
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يوفر الوصول إلى أنواع مختلفة من السمات التي تم تجاوزها.
type: docs
url: /ar/com.aspose.slides/ioverridethememanager/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

يوفر الوصول إلى أنواع مختلفة من السمات التي تم تجاوزها.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعالة الموروثة أم لا. |
| [getOverrideTheme()](#getOverrideTheme--) | إرجاع كائن السمة المتجاوزة. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | إرجاع كائن السمة المتجاوزة. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعالة الموروثة أم لا. لتمكين OverrideTheme من التجاوز استخدم أساليب OverrideTheme.Init*(). لإلغاء تمكين OverrideTheme من التجاوز استخدم طريقة OverrideTheme.Clear(). قيمة منطقية للقراءة فقط.

**الإرجاع:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

إرجاع كائن السمة المتجاوزة. قراءة/كتابة [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**الإرجاع:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

إرجاع كائن السمة المتجاوزة. قراءة/كتابة [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**المعلمات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |