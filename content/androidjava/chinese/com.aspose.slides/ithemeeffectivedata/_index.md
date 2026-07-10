---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 不可变对象，包含有效的主题属性。
type: docs
url: /zh/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

不可变对象，包含有效的主题属性。

--------------------

此接口与 [ITheme](../../com.aspose.slides/itheme) 接口一起使用，以返回已应用继承的有效格式化值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | 返回颜色方案。 |
| [getFontScheme()](#getFontScheme--) | 返回字体方案。 |
| [getFormatScheme()](#getFormatScheme--) | 返回形状格式方案。 |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

返回颜色方案。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| styleColor | java.lang.Integer | 颜色 java.lang.Integer |

**返回:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - 颜色方案 [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

返回字体方案。只读 [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)。

**返回:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

返回形状格式方案。只读 [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)。

**返回:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)