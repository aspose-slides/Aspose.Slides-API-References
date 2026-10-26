---
title: MasterTheme
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个主主题。
type: docs
url: /zh/com.aspose.slides/mastertheme/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**所有实现的接口:**  
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

表示一个主主题。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 返回颜色方案。 |
| [getFontScheme()](#getFontScheme--) | 返回字体方案。 |
| [getFormatScheme()](#getFormatScheme--) | 返回形状格式方案。 |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 返回附加颜色方案的集合。 |
| [getName()](#getName--) | 返回主题的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回主题的名称。 |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

返回颜色方案。只读 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**返回：**  
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

返回字体方案。只读 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**返回：**  
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

返回形状格式方案。只读 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**返回：**  
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

返回附加颜色方案的集合。这些方案不会影响演示文稿的外观，它们可以被选择为幻灯片的主颜色方案。只读 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)。

**返回：**  
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)

### getName() {#getName--}
```
public final String getName()
```

返回主题的名称。读/写 String。

**返回：**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

返回主题的名称。读/写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**  
long