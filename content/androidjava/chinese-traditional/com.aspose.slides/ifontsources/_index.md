---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /zh-hant/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

提供外部字型的檔案和記憶體來源。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Folders containing font files. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Folders containing font files. |
| [getMemoryFonts()](#getMemoryFonts--) | A collection of fonts represented as byte arrays. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | A collection of fonts represented as byte arrays. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

包含字型檔案的資料夾。所有位於這些資料夾中的字型檔案都會被納入集合。會遞迴搜尋資料夾。

**傳回：**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

包含字型檔案的資料夾。所有位於這些資料夾中的字型檔案都會被納入集合。會遞迴搜尋資料夾。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

以位元組陣列表示的字型集合。

**傳回：**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

以位元組陣列表示的字型集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte[][] |  |