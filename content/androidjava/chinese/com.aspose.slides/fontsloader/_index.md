---
title: FontsLoader
second_title: Aspose.Slides for Android Java API 参考
description: 用于加载用户定义的自定义字体的类。
type: docs
url: /zh/com.aspose.slides/fontsloader/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)  
```
public final class FontsLoader implements IFontsLoader
```

用于加载用户定义的自定义字体的类。应在创建任何演示文稿对象之前使用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | 添加额外的文件夹以搜索字体。 |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | 从二进制数据添加字体 |
| [getFontFolders()](#getFontFolders--) | 获取字体文件夹。 |
| [clearCache()](#clearCache--) | 释放用户定义的所有自定义字体 |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


添加额外的文件夹以搜索字体。

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // folders to seek fonts
>  String[] folders = new String[] { dataDir };
>  // Load the custom font directory fonts
>  FontsLoader.loadExternalFonts(folders);
>  // Do Some work and perform presentation/slides rendering
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Clear Font Cachce
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| directories | java.lang.String[] | Directories to read additional fonts. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

Adds font from the binary data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Font's data |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

Gets font folders. Returns folders that have been added with LoadExternalFonts method as well as system font folders

**Returns:**
java.lang.String[] - array containing folder names
### clearCache() {#clearCache--}
```
public static void clearCache()

Releases all custom fonts defined by user

--------------------

This method needs to clear cache with custom fonts defined by user.