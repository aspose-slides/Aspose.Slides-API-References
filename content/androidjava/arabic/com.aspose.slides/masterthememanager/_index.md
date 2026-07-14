---
title: MasterThemeManager
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يوفر وصولًا إلى سمة العرض الرئيسية.
type: docs
url: /ar/com.aspose.slides/masterthememanager/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)  
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

**يوفر وصولًا إلى سمة العرض الرئيسية.**  
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | يراجع كائن السمة المتجاوزة. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | يراجع كائن السمة المتجاوزة. |
| [createThemeEffective()](#createThemeEffective--) | يراجع كائن السمة. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعّالة الموروثة (Presentation.MasterTheme) أم لا. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعّالة الموروثة (Presentation.MasterTheme) أم لا. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | يطبق مخطط ألوان إضافي على شريحة. |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

يراجع كائن السمة المتجاوزة. قراءة/كتابة [IMasterTheme](../../com.aspose.slides/imastertheme).

**الإرجاع:**  
[IMasterTheme](../../com.aspose.slides/imastertheme)

### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

يراجع كائن السمة المتجاوزة. قراءة/كتابة [IMasterTheme](../../com.aspose.slides/imastertheme).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

يرجع كائن السمة.

**الإرجاع:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعّالة الموروثة (Presentation.MasterTheme) أم لا. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

يحدد ما إذا كان OverrideTheme يتجاوز السمة الفعّالة الموروثة (Presentation.MasterTheme) أم لا. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

يطبق مخطط ألوان إضافي على شريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) كائن. |