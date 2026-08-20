---
title: FontScheme
second_title: Aspose.Slides for Java API 參考
description: 儲存主題定義的字型。
type: docs
url: /zh-hant/com.aspose.slides/fontscheme/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject
```
public class FontScheme implements IFontScheme, IDOMObject
```

儲存主題定義的字型。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getMinor()](#getMinor--) | 返回投影片 "body" 部分的字型集合。 |
| [getMajor()](#getMajor--) | 返回投影片 "heading" 部分的字型集合。 |
| [getName()](#getName--) | 返回字型方案名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回字型方案名稱。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```


返回投影片 "body" 部分的字型集合。唯讀 [IFonts](../../com.aspose.slides/ifonts)。

**傳回值:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```


返回投影片 "heading" 部分的字型集合。可讀寫 [IFonts](../../com.aspose.slides/ifonts)。

**傳回值:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public final String getName()
```


返回字型方案名稱。可讀寫 String。

**傳回值:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


返回字型方案名稱。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent\_Immediate 物件。唯讀 IDOMObject。

**傳回值:**
com.aspose.slides.IDOMObject