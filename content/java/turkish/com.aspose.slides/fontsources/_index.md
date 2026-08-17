---
title: FontSources
second_title: Aspose.Slides for Java API Referansı
description: Harici yazı tipleri için dosya ve bellek kaynakları sağlar.
type: docs
url: /tr/com.aspose.slides/fontsources/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Dış yazı tipleri için dosya ve bellek kaynakları sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontSources()](#FontSources--) | Yeni varsayılan yazı tipi seçenekleri oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Yazı tipi dosyalarını içeren klasörler. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Yazı tipi dosyalarını içeren klasörler. |
| [getMemoryFonts()](#getMemoryFonts--) | Bayt dizileri olarak temsil edilen bir yazı tipi koleksiyonu. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Bayt dizileri olarak temsil edilen bir yazı tipi koleksiyonu. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Yeni varsayılan yazı tipi seçenekleri oluşturur.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Yazı tipi dosyalarını içeren klasörler. Bu klasörlerde bulunan tüm yazı tipi dosyaları koleksiyona dahil edilir. Rekürsif olarak aranan klasörler.

**Dönüş Değeri:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Yazı tipi dosyalarını içeren klasörler. Bu klasörlerde bulunan tüm yazı tipi dosyaları koleksiyona dahil edilir. Rekürsif olarak aranan klasörler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


Bayt dizileri olarak temsil edilen bir yazı tipi koleksiyonu.

**Dönüş Değeri:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


Bayt dizileri olarak temsil edilen bir yazı tipi koleksiyonu.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | byte[][] |  |