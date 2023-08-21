---
title: FontsLoader
second_title: Aspose.Slides for Android via Java API Reference
description: Class for loading custom fonts defined by user.
type: docs
url: /com.aspose.slides/fontsloader/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Class for loading custom fonts defined by user. Should be used before creating any presentation objects.
## Methods

| Method | Description |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Adds additional folders to seek fonts. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Adds font from the binary data |
| [getFontFolders()](#getFontFolders--) | Gets font folders. |
| [clearCache()](#clearCache--) | Releases all custom fonts defined by user |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Adds additional folders to seek fonts.

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
```


Releases all custom fonts defined by user

--------------------

This method needs to clear cache with custom fonts defined by user.

