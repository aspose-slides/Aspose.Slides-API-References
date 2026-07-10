---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: 提供外部字体的文件和内存源。
type: docs
url: /zh/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

提供外部字体的文件和内存源。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Folders containing font files. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Folders containing font files. |
| [getMemoryFonts()](#getMemoryFonts--) | A collection of fonts represented as byte arrays. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | A collection of fonts represented as byte arrays. |

### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

文件夹包含字体文件。位于这些文件夹中的所有字体文件都会被包含在集合中。对文件夹进行递归搜索。

**返回:**  
java.lang.String[]

### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

文件夹包含字体文件。位于这些文件夹中的所有字体文件都会被包含在集合中。对文件夹进行递归搜索。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

以字节数组形式表示的字体集合。

**返回:**  
byte[][]

### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

以字节数组形式表示的字体集合。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[][] |  |