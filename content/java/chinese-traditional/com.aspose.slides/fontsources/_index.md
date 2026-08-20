---
title: FontSources
second_title: Aspose.Slides Java API 參考
description: 提供外部字型的檔案與記憶體來源。
type: docs
url: /zh-hant/com.aspose.slides/fontsources/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

提供外部字型的檔案與記憶體來源。
## 建構函式

| 建構子 | 說明 |
| --- | --- |
| [FontSources()](#FontSources--) | 建立新的預設字型選項。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | 包含字型檔案的資料夾。 |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | 包含字型檔案的資料夾。 |
| [getMemoryFonts()](#getMemoryFonts--) | 以位元組陣列表示的字型集合。 |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | 以位元組陣列表示的字型集合。 |
### FontSources() {#FontSources--}
```
public FontSources()
```


建立新的預設字型選項。

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


包含字型檔案的資料夾。此資料夾中的所有字型檔案皆會被納入集合。會遞迴搜尋資料夾。

**回傳值：**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


包含字型檔案的資料夾。此資料夾中的所有字型檔案皆會被納入集合。會遞迴搜尋資料夾。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


以位元組陣列表示的字型集合。

**回傳值：**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


以位元組陣列表示的字型集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte[][] |  |