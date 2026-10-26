---
title: BaseOverrideThemeManager
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 为提供对不同类型覆盖主题访问的类的基类。
type: docs
url: /zh/com.aspose.slides/baseoverridethememanager/
---
**继承：**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**所有实现的接口：**  
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)  
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

提供对不同类型覆盖主题访问的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | 返回覆盖主题对象。 |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | 返回覆盖主题对象。 |
| [createThemeEffective()](#createThemeEffective--) | 返回主题对象。 |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 确定 OverrideTheme 是否覆盖继承的有效主题。 |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | 将额外的配色方案应用于幻灯片。 |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

返回覆盖主题对象。 可读写 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**返回：**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)

### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

返回覆盖主题对象。 可读写 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

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

确定 OverrideTheme 是否覆盖继承的有效主题。要启用 OverrideTheme 进行覆盖，请使用 OverrideTheme.Init*() 方法。要禁用 OverrideTheme 的覆盖，请使用 OverrideTheme.Clear() 方法。只读布尔值。

**返回：**  
boolean

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

将额外的配色方案应用于幻灯片。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | 该 [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) 对象。 |