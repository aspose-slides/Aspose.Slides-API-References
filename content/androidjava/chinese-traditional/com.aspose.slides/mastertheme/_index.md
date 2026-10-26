---
title: MasterTheme
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一個主題。
type: docs
url: /zh-hant/com.aspose.slides/mastertheme/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**已實作的介面：**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

表示一個主題。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 傳回顏色配置。 |
| [getFontScheme()](#getFontScheme--) | 傳回字型配置。 |
| [getFormatScheme()](#getFormatScheme--) | 傳回圖形格式配置。 |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 傳回額外顏色配置的集合。 |
| [getName()](#getName--) | 傳回主題的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 傳回主題的名稱。 |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

傳回顏色配置。唯讀 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**傳回值：**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

傳回字型配置。唯讀 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**傳回值：**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

傳回圖形格式配置。唯讀 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**傳回值：**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

傳回額外顏色配置的集合。這些配置不會影響簡報的外觀，可選擇為投影片的主要顏色配置。唯讀 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)。

**傳回值：**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

傳回主題的名稱。可讀寫 String。

**傳回值：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

傳回主題的名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回值：**
long