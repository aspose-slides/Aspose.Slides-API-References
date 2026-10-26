---
title: FontsLoader
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Kullanıcı tarafından tanımlanan özel yazı tiplerini yüklemek için sınıf.
type: docs
url: /tr/com.aspose.slides/fontsloader/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Kullanıcı tarafından tanımlanan özel yazı tiplerini yüklemek için sınıf. Herhangi bir sunum nesnesi oluşturmadan önce kullanılmalıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Adds additional folders to seek fonts. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Adds font from the binary data |
| [getFontFolders()](#getFontFolders--) | Gets font folders. |
| [clearCache()](#clearCache--) | Releases all custom fonts defined by user |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Yazı tiplerini bulmak için ek klasörler ekler.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // yazı tiplerini aramak için klasörler
>  String[] folders = new String[] { dataDir };
>  // Özel yazı tipi klasörünü yükle
>  FontsLoader.loadExternalFonts(folders);
>  // Bazı işler yap ve sunum/slayt oluşturmayı gerçekleştir
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Yazı tipi önbelleğini temizle
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| directories | java.lang.String[] | Ek yazı tiplerini okumak için dizinler. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


İkili veriden yazı tipini ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Yazı tipinin verisi |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Yazı tipi klasörlerini alır. LoadExternalFonts yöntemiyle eklenen klasörlerin yanı sıra sistem yazı tipi klasörlerini de döndürür.

**Döndürür:**
java.lang.String[] - klasör adlarını içeren dizi
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Kullanıcı tarafından tanımlanan tüm özel yazı tiplerini serbest bırakır

--------------------

Bu yöntemin, kullanıcı tarafından tanımlanan özel yazı tipleriyle önbelleği temizlemesi gerekir.