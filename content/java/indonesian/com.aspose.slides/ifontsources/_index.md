---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /id/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Menyediakan sumber file dan memori untuk font eksternal.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Folder yang berisi file font. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Folder yang berisi file font. |
| [getMemoryFonts()](#getMemoryFonts--) | Koleksi font yang direpresentasikan sebagai array byte. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Koleksi font yang direpresentasikan sebagai array byte. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Folder yang berisi file font. Semua file font yang berada di folder ini termasuk dalam koleksi. Folder yang dicari secara rekursif.

**Mengembalikan:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Folder yang berisi file font. Semua file font yang berada di folder ini termasuk dalam koleksi. Folder yang dicari secara rekursif.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Koleksi font yang direpresentasikan sebagai array byte.

**Mengembalikan:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Koleksi font yang direpresentasikan sebagai array byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte[][] |  |