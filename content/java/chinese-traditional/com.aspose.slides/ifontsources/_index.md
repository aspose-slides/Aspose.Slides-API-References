---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: 提供外部字型的檔案與記憶體來源。
type: docs
url: /zh-hant/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

提供檔案與記憶體來源給外部字型。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | 包含字型檔案的資料夾。 |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | 包含字型檔案的資料夾。 |
| [getMemoryFonts()](#getMemoryFonts--) | 以 byte 陣列表示的字型集合。 |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | 以 byte 陣列表示的字型集合。 |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

包含字型檔案的資料夾。位於這些資料夾中的所有字型檔案都會被納入集合。會遞迴搜尋資料夾。

**傳回：**  
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

包含字型檔案的資料夾。位於這些資料夾中的所有字型檔案都會被納入集合。會遞迴搜尋資料夾。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

以 byte 陣列表示的字型集合。

**傳回：**  
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

以 byte 陣列表示的字型集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte[][] |  |