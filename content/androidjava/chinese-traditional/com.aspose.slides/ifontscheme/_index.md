---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: 儲存主題定義的字型。
type: docs
url: /zh-hant/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

儲存主題定義的字型。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getMinor()](#getMinor--) | Returns the fonts collection for a "body" part of the slide. |
| [getMajor()](#getMajor--) | Returns the fonts collection for a "heading" part of the slide. |
| [getName()](#getName--) | Returns the font scheme name. |
| [setName(String value)](#setName-java.lang.String-) | Returns the font scheme name. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

返回投影片「body」部分的字型集合。唯讀 [IFonts](../../com.aspose.slides/ifonts)。

**返回：**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

返回投影片「heading」部分的字型集合。唯讀 [IFonts](../../com.aspose.slides/ifonts)。

**返回：**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

返回字型方案名稱。可讀寫 String。

**返回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回字型方案名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |