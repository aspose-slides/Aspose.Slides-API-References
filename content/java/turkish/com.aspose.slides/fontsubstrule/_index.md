---
title: FontSubstRule
second_title: Aspose.Slides for Java API Referansı
description: Yazı tipi yerine koyma bilgilerini temsil eder
type: docs
url: /tr/com.aspose.slides/fontsubstrule/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Yazı tipi yerine koyma bilgilerini temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Yeni bir örnek oluşturur. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Yeni bir örnek oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Değiştirilecek font. |
| [getDestFont()](#getDestFont--) | Değiştirme için kullanılacak font. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Yerine koyma için uygulanacak kural. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

Yeni bir örnek oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Kaynak font. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Hedef font. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

Yeni bir örnek oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Kaynak font. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Hedef font. |
| fontSubstRule | int | Font yerine koyma kuralı. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

Değiştirilecek font. Salt okunur [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

Değiştirme için kullanılacak font. Salt okunur [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

Yerine koyma için uygulanacak kural. Salt okunur [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Döndürür:**
int