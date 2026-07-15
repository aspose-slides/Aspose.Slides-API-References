---
title: FontScheme
second_title: Aspose.Slides for Android 的 Java API 參考
description: 儲存主題定義的字型。
type: docs
url: /zh-hant/com.aspose.slides/fontscheme/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject
```
public class FontScheme implements IFontScheme, IDOMObject
```

儲存主題定義的字型。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMinor()](#getMinor--) | 返回投影片「body」部份的字型集合。 |
| [getMajor()](#getMajor--) | 返回投影片「heading」部份的字型集合。 |
| [getName()](#getName--) | 返回字型方案名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回字型方案名稱。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```

返回投影片「body」部份的字型集合。唯讀 [IFonts](../../com.aspose.slides/ifonts)。

**返回：**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```

返回投影片「heading」部份的字型集合。唯讀 [IFonts](../../com.aspose.slides/ifonts)。

**返回：**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public final String getName()
```

返回字型方案名稱。讀寫 String。

**返回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

返回字型方案名稱。讀寫 String。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent\_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject