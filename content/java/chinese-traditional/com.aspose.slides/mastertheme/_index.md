---
title: MasterTheme
second_title: Aspose.Slides for Java API 參考
description: 表示一個母版主題。
type: docs
url: /zh-hant/com.aspose.slides/mastertheme/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**全部已實作的介面：**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

表示一個母版主題。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 傳回色彩配置方案。 |
| [getFontScheme()](#getFontScheme--) | 傳回字型配置方案。 |
| [getFormatScheme()](#getFormatScheme--) | 傳回形狀格式配置方案。 |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 傳回額外色彩配置方案的集合。 |
| [getName()](#getName--) | 傳回佈景主題的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 傳回佈景主題的名稱。 |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


傳回色彩配置方案。唯讀 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**傳回：**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


傳回字型配置方案。唯讀 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**傳回：**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


傳回形狀格式配置方案。唯讀 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**傳回：**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


傳回額外色彩配置方案的集合。這些配置方案不會影響簡報的外觀，它們可被選為投影片的主要色彩配置方案。唯讀 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)。

**傳回：**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


傳回佈景主題的名稱。可讀寫 String。

**傳回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


傳回佈景主題的名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```


版本。唯讀 long。

**傳回：**
long