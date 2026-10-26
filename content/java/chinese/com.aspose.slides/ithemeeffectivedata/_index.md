---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference 的中文文档
description: 包含有效主题属性的不可变对象。
type: docs
url: /zh/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

包含有效主题属性的不可变对象。

--------------------

此接口与 [ITheme](../../com.aspose.slides/itheme) 接口一起使用，以返回已应用继承的有效格式化值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | 返回颜色方案。 |
| [getFontScheme()](#getFontScheme--) | 返回字体方案。 |
| [getFormatScheme()](#getFormatScheme--) | 返回形状格式方案。 |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


返回颜色方案。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**返回值:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


返回字体方案。只读 [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)。

**返回值:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


返回形状格式方案。只读 [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)。

**返回值:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)