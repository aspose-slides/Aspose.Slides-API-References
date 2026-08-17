---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: 提供外部字体的文件和内存来源。
type: docs
url: /zh/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

提供外部字体的文件和内存来源。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | 包含字体文件的文件夹。 |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | 包含字体文件的文件夹。 |
| [getMemoryFonts()](#getMemoryFonts--) | 以字节数组表示的字体集合。 |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | 以字节数组表示的字体集合。 |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

包含字体文件的文件夹。位于这些文件夹中的所有字体文件都包含在集合中。递归搜索的文件夹。

**返回:**  
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

包含字体文件的文件夹。位于这些文件夹中的所有字体文件都包含在集合中。递归搜索的文件夹。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

以字节数组表示的字体集合。

**返回:**  
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

以字节数组表示的字体集合。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[][] |  |