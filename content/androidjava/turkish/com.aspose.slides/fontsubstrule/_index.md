---
title: FontSubstRule
second_title: Android için Aspose.Slides Java API Referansı
description: Font ikame bilgilerini temsil eder
type: docs
url: /tr/com.aspose.slides/fontsubstrule/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Font ikame bilgilerini temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Yeni bir örnek oluşturur. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Yeni bir örnek oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Font to substitute. |
| [getDestFont()](#getDestFont--) | Font to use for substitution. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Rule to apply for substitution. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Yeni bir örnek oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Source font. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destination font. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Yeni bir örnek oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Source font. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destination font. |
| fontSubstRule | int | Font subst rule. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


İkame edilecek yazı tipi. Salt okunur [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


İkame için kullanılacak yazı tipi. Salt okunur [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


İkame için uygulanacak kural. Salt okunur [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Döndürür:**
int