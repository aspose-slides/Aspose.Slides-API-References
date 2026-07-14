---
title: BaseOverrideThemeManager
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: الفئة الأساسية للفئات التي توفر الوصول إلى أنواع مختلفة من السمات المتجاوزة.
type: docs
url: /ar/com.aspose.slides/baseoverridethememanager/
---
**الوراثة:**  
[com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)  
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

الفئة الأساسية للفئات التي توفر الوصول إلى أنواع مختلفة من السمات المتجاوزة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | يعيد كائن السمة المتجاوزة. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | يعيد كائن السمة المتجاوزة. |
| [createThemeEffective()](#createThemeEffective--) | يعيد كائن السمة. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعالة الموروثة أم لا. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | يطبق مخطط ألوان إضافي على شريحة. |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

يعيد كائن السمة المتجاوزة. قابل للقراءة والكتابة [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**القيمة المرجعة:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)

### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

يعيد كائن السمة المتجاوزة. قابل للقراءة والكتابة [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

يعيد كائن السمة.

**القيمة المرجعة:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعالة الموروثة أم لا. لتمكين OverrideTheme من التجاوز استخدم طرق OverrideTheme.Init\*(). لتعطيل OverrideTheme من التجاوز استخدم طريقة OverrideTheme.Clear(). للقراءة فقط boolean.

**القيمة المرجعة:**  
boolean

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

يطبق مخطط ألوان إضافي على شريحة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | الكائن [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |