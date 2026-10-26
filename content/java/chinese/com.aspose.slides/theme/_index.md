---
title: Theme
second_title: Aspose.Slides for Java API 参考
description: 表示一个主题。
type: docs
url: /zh/com.aspose.slides/theme/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject  
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

表示一个主题。  
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 返回颜色方案。 |
| [getFontScheme()](#getFontScheme--) | 返回字体方案。 |
| [getFormatScheme()](#getFormatScheme--) | 返回形状格式方案。 |
| [getPresentation()](#getPresentation--) | 返回父演示文稿。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效主题数据。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |

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

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

获取应用继承后的有效主题数据。

--------------------

> ```
> This example demonstrates getting effective theme properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IThemeEffectiveData effectiveTheme  = pres.getSlides().get_Item(0).getThemeManager().getOverrideTheme().getEffective();
>  	System.out.println("Font scheme name: " + effectiveTheme.getFontScheme().getName());
>  	System.out.println("Major latin font: " + effectiveTheme.getFontScheme().getMajor().getLatinFont().getFontName());
>  	System.out.println("Minor latin font: " + effectiveTheme.getFontScheme().getMinor().getLatinFont().getFontName());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**返回：**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - 一个 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**  
com.aspose.slides.IDOMObject

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回父 IPresentationComponent。只读 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回：**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

版本。只读 long。

**返回：**  
long