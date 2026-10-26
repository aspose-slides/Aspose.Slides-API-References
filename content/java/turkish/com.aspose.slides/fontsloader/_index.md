---
title: FontsLoader
second_title: Aspose.Slides for Java API Referansı
description: Kullanıcı tarafından tanımlanan özel yazı tiplerini yüklemek için sınıf.
type: docs
url: /tr/com.aspose.slides/fontsloader/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Kullanıcı tarafından tanımlanan özel yazı tiplerini yüklemek için sınıf. Herhangi bir sunum nesnesi oluşturmadan önce kullanılmalıdır.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Ek yazı tiplerini aramak için ek klasörler ekler. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | İkili veriden yazı tipi ekler |
| [getFontFolders()](#getFontFolders--) | Yazı tipi klasörlerini alır. |
| [clearCache()](#clearCache--) | Kullanıcı tarafından tanımlanan tüm özel yazı tiplerini serbest bırakır |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Ek yazı tiplerini aramak için ek klasörler ekler.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // yazı tiplerini aramak için klasörler
>  String[] folders = new String[] { dataDir };
>  // Özel yazı tipi dizini klasörlerini yükle
>  FontsLoader.loadExternalFonts(folders);
>  // Bazı işlemleri yap ve sunum/slaytları render et
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Yazı Tipi Önbelleğini Temizle
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| directories | java.lang.String[] | Ek yazı tiplerini okuma klasörleri. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


İkili veriden yazı tipi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Yazı tipinin verisi |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Yazı tipi klasörlerini alır. LoadExternalFonts yöntemiyle eklenen klasörlerin yanı sıra sistem yazı tipi klasörlerini döndürür.

**Döndürür:**
java.lang.String[] - klasör adlarını içeren dizi
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Kullanıcı tarafından tanımlanan tüm özel yazı tiplerini serbest bırakır

--------------------

Bu yöntem, kullanıcı tarafından tanımlanan özel yazı tipleriyle önbelleği temizlemelidir.