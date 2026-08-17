---
title: MasterThemeManager
second_title: Aspose.Slides for Java API 参考
description: 提供对演示文稿主主题的访问。
type: docs
url: /zh/com.aspose.slides/masterthememanager/
---
**继承：**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**所有实现的接口：**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

提供对演示文稿主主题的访问。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | 返回覆盖主题对象。 |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | 返回覆盖主题对象。 |
| [createThemeEffective()](#createThemeEffective--) | 返回主题对象。 |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 确定 OverrideTheme 是否覆盖继承的有效主题 (Presentation.MasterTheme)。 |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | 确定 OverrideTheme 是否覆盖继承的有效主题 (Presentation.MasterTheme)。 |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | 对幻灯片应用额外的配色方案。 |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

返回覆盖主题对象。读/写 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**返回：**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

返回覆盖主题对象。读/写 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

返回主题对象。

**返回：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

确定 OverrideTheme 是否覆盖继承的有效主题 (Presentation.MasterTheme)。读/写 boolean。

**返回：**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

确定 OverrideTheme 是否覆盖继承的有效主题 (Presentation.MasterTheme)。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

对幻灯片应用额外的配色方案。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) 对象。 |