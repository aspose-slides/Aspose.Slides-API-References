---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Harici yazı tipleri için dosya ve bellek kaynakları sağlar.
type: docs
url: /tr/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Harici yazı tipleri için dosya ve bellek kaynakları sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Yazı tipi dosyalarını içeren klasörler. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Yazı tipi dosyalarını içeren klasörler. |
| [getMemoryFonts()](#getMemoryFonts--) | Bayt dizileri olarak temsil edilen bir yazı tipi koleksiyonu. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Bayt dizileri olarak temsil edilen bir yazı tipi koleksiyonu. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Yazı tipi dosyalarını içeren klasörler. Bu klasörlerde bulunan tüm yazı tipi dosyaları koleksiyona dahil edilir. Alt klasörler de yinelemeli olarak aranır.

**Döndürür:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Yazı tipi dosyalarını içeren klasörler. Bu klasörlerde bulunan tüm yazı tipi dosyaları koleksiyona dahil edilir. Alt klasörler de yinelemeli olarak aranır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Bayt dizileri olarak temsil edilen bir yazı tipi koleksiyonu.

**Döndürür:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Bayt dizileri olarak temsil edilen bir yazı tipi koleksiyonu.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte[][] |  |