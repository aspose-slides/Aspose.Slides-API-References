---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /tr/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Provides file and memory sources for external fonts.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Yazı tipi dosyalarını içeren klasörler. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Yazı tipi doslarını içeren klasörler. |
| [getMemoryFonts()](#getMemoryFonts--) | Byte dizileriyle temsil edilen bir font koleksiyonu. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Byte dizileriyle temsil edilen bir font koleksiyonu. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Yazı tipi dosyalarını içeren klasörler. Bu klasörlerde bulunan tüm font dosyaları koleksiyona dahil edilir. Rekürsif olarak aranan klasörler.

**Döndürür:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Yazı tipi dosyalarını içeren klasörler. Bu klasörlerde bulunan tüm font dosyaları koleksiyona dahil edilir. Rekürsif olarak aranan klasörler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


Byte dizileriyle temsil edilen bir font koleksiyonu.

**Döndürür:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


Byte dizileriyle temsil edilen bir font koleksiyonu.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte[][] |  |