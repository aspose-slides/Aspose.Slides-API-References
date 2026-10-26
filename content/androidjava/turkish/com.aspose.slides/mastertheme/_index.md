---
title: MasterTheme
second_title: Java API Referansı ile Android için Aspose.Slides
description: Bir ana temayı temsil eder.
type: docs
url: /tr/com.aspose.slides/mastertheme/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Bir ana temayı temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Renk şemasını döndürür. |
| [getFontScheme()](#getFontScheme--) | Yazı tipi şemasını döndürür. |
| [getFormatScheme()](#getFormatScheme--) | Şekil format şemasını döndürür. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Ek renk şemalarının koleksiyonunu döndürür. |
| [getName()](#getName--) | Bir temanın adını döndürür. |
| [setName(String value)](#setName-java.lang.String-) | Bir temanın adını döndürür. |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Renk şemasını döndürür. Salt-okunur [IColorScheme](../../com.aspose.slides/icolorscheme).

**Döndürür:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Yazı tipi şemasını döndürür. Salt-okunur [IFontScheme](../../com.aspose.slides/ifontscheme).

**Döndürür:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Şekil format şemasını döndürür. Salt-okunur [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Döndürür:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Ek renk şemalarının koleksiyonunu döndürür. Bu şemalar sunumun görünümünü etkilemez, bir slayt için ana renk şeması olarak seçilebilir. Salt-okunur [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Döndürür:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

Bir temanın adını döndürür. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Bir temanın adını döndürür. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versiyon. Salt-okunur long.

**Döndürür:**
long