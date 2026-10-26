---
title: IFontScheme
second_title: Aspose.Slides for Java API 參考
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
| [getMinor()](#getMinor--) | 傳回投影片的 "body" 部分的字型集合。 |
| [getMajor()](#getMajor--) | 傳回投影片的 "heading" 部分的字型集合。 |
| [getName()](#getName--) | 傳回字型方案名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 傳回字型方案名稱。 |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


傳回投影片的 "body" 部分的字型集合。唯讀 [IFonts](../../com.aspose.slides/ifonts)。

**傳回值:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


傳回投影片的 "heading" 部分的字型集合。唯讀 [IFonts](../../com.aspose.slides/ifonts)。

**傳回值:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


傳回字型方案名稱。可讀寫 String。

**傳回值:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


傳回字型方案名稱。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |