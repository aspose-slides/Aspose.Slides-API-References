---
title: BaseOverrideThemeManager
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: الفئة الأساسية للفئات التي توفر الوصول إلى أنواع مختلفة من السمات المتجاوزة.
type: docs
url: /ar/com.aspose.slides/baseoverridethememanager/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

الفئة الأساسية للفئات التي توفر الوصول إلى أنواع مختلفة من السمات المتجاوزة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | إرجاع كائن السمة المتجاوزة. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | إرجاع كائن السمة المتجاوزة. |
| [createThemeEffective()](#createThemeEffective--) | إرجاع كائن السمة. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | تحديد ما إذا كان OverrideTheme يتجاوز السمة الفعالة الموروثة أم لا. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | تطبيق مخطط ألوان إضافي على الشريحة. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

إرجاع كائن السمة المتجاوزة. قراءة/كتابة [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**القيمة المرجعة:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

إرجاع كائن السمة المتجاوزة. قراءة/كتابة [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

إرجاع كائن السمة.

**القيمة المرجعة:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

تحديد ما إذا كان OverrideTheme يتجاوز السمة الفعالة الموروثة أم لا. لتمكين OverrideTheme من التجاوز استخدم طرق OverrideTheme.Init\*(). لتعطيل OverrideTheme من التجاوز استخدم طريقة OverrideTheme.Clear(). ثابت للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

تطبيق مخطط ألوان إضافي على الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | الكائن [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |