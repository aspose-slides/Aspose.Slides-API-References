---
title: FontSources
second_title: Aspose.Slides for Java API 参考
description: 提供用于外部字体的文件和内存来源。
type: docs
url: /zh/com.aspose.slides/fontsources/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

提供用于外部字体的文件和内存来源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontSources()](#FontSources--) | 创建新的默认字体选项。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | 包含字体文件的文件夹。 |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | 包含字体文件的文件夹。 |
| [getMemoryFonts()](#getMemoryFonts--) | 以字节数组形式表示的字体集合。 |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | 以字节数组形式表示的字体集合。 |
### FontSources() {#FontSources--}
```
public FontSources()
```

创建新的默认字体选项。

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

包含字体文件的文件夹。位于这些文件夹中的所有字体文件都会被纳入集合。递归搜索文件夹。

**返回：**  
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

包含字体文件的文件夹。位于这些文件夹中的所有字体文件都会被纳入集合。递归搜索文件夹。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

以字节数组形式表示的字体集合。

**返回：**  
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

以字节数组形式表示的字体集合。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[][] |  |