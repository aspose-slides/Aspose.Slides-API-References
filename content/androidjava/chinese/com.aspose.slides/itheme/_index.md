---
title: ITheme
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个主题。
type: docs
url: /zh/com.aspose.slides/itheme/
---
**所有实现的接口：**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

表示一个主题。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 返回颜色方案。 |
| [getFontScheme()](#getFontScheme--) | 返回字体方案。 |
| [getFormatScheme()](#getFormatScheme--) | 返回形状格式方案。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效主题数据。 |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


返回颜色方案。只读 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**返回：**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


返回字体方案。只读 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**返回：**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


返回形状格式方案。只读 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**返回：**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


获取应用继承后的有效主题数据。

**返回：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - 一个 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).