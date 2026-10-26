---
title: FontsLoader
second_title: Referensi API Aspose.Slides untuk Java
description: Kelas untuk memuat font khusus yang ditentukan oleh pengguna.
type: docs
url: /id/com.aspose.slides/fontsloader/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Kelas untuk memuat font khusus yang ditentukan oleh pengguna. Harus digunakan sebelum membuat objek presentasi apa pun.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Menambahkan folder tambahan untuk mencari font. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Menambahkan font dari data biner |
| [getFontFolders()](#getFontFolders--) | Mendapatkan folder font. |
| [clearCache()](#clearCache--) | Melepaskan semua font khusus yang ditentukan oleh pengguna |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

Menambahkan folder tambahan untuk mencari font.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // folder untuk mencari font
>  String[] folders = new String[] { dataDir };
>  // Muat font dari direktori khusus
>  FontsLoader.loadExternalFonts(folders);
>  // Lakukan beberapa pekerjaan dan lakukan rendering presentasi/slides
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Bersihkan Cache Font
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| directories | java.lang.String[] | Direktori untuk membaca font tambahan. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

Menambahkan font dari data biner

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data font |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

Mendapatkan folder font. Mengembalikan folder yang telah ditambahkan dengan metode LoadExternalFonts serta folder font sistem

**Mengembalikan:**
java.lang.String[] - array berisi nama folder
### clearCache() {#clearCache--}
```
public static void clearCache()
```

Melepaskan semua font khusus yang ditentukan oleh pengguna

--------------------

Metode ini perlu menghapus cache dengan font khusus yang ditentukan oleh pengguna.