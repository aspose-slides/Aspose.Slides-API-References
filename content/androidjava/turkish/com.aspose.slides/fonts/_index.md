---
title: Fonts
second_title: Aspose.Slides for Android via Java API Referansı
description: Yazı tipleri koleksiyonu.
type: docs
url: /tr/com.aspose.slides/fonts/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Yazı tipi koleksiyonu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Sunumdaki tüm betik yazı tipi tanımlarının bir sözlüğünü döndürür. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Sunum temasından belirli bir betik etiketine ilişkili yazı tipi adını alır. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Belirli bir betik etiketine bir yazı tipi adı atar; bu, betiğin metninin sunumda nasıl görüntüleneceğini tanımlar. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Temanın yazı tipi koleksiyonundan belirli bir betik etiketiyle ilişkili yazı tipi ayarını kaldırır. |
| [getLatinFont()](#getLatinFont--) | Latin yazı tipini döndürür veya ayarlar. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin yazı tipini döndürür veya ayarlar. |
| [getEastAsianFont()](#getEastAsianFont--) | Doğu Asya yazı tipini döndürür veya ayarlar. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Doğu Asya yazı tipini döndürür veya ayarlar. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Karmaşık betik yazı tipini döndürür veya ayarlar. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Karmaşık betik yazı tipini döndürür veya ayarlar. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Sunumdaki tüm betik yazı tipi tanımlarının bir sözlüğünü döndürür.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Döndürür:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Betik kodlarını yazı tipi adlarına eşleyen bir sözlük.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

Sunum temasından belirli bir betik etiketine ilişkili yazı tipi adını alır.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Bir yazı sistemi tanımlamak için kullanılan BCP-47 betik kodu (ör. "Latn", "Cyrl", "Jpan"). |

**Döndürür:**
java.lang.String - Belirtilen betik için kullanılan yazı tipi adı, betik tanımlı değilse  null  değerini döndürür.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Belirli bir betik etiketine bir yazı tipi adı atar; bu, betiğin metninin sunumda nasıl görüntüleneceğini tanımlar.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Bir yazı sistemi tanımlamak için kullanılan BCP-47 betik kodu (ör. "Arab", "Hebr", "Hans"). |
| fontName | java.lang.String | Belirtilen betiğe atanacak yazı tipinin adı. |
### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Temanın yazı tipi koleksiyonundan belirli bir betik etiketiyle ilişkili yazı tipi ayarını kaldırır.

--------------------

> ```
> Bu örnek, İbranice betiği için yazı tipi eşlemesini nasıl kaldıracağınızı gösterir:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Bir yazı sistemi tanımlamak için kullanılan BCP-47 betik kodu. |
### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Latin yazı tipini döndürür veya ayarlar. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Latin yazı tipini döndürür veya ayarlar. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Doğu Asya yazı tipini döndürür veya ayarlar. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Doğu Asya yazı tipini döndürür veya ayarlar. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Karmaşık betik yazı tipini döndürür veya ayarlar. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Karmaşık betik yazı tipini döndürür veya ayarlar. Okuma/yazma [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |