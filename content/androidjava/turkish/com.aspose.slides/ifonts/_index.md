---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Yazı tipleri koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Yazı tipleri koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Latin yazı tipini getirir veya ayarlar. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin yazı tipini getirir veya ayarlar. |
| [getEastAsianFont()](#getEastAsianFont--) | Doğu Asya yazı tipini getirir veya ayarlar. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Doğu Asya yazı tipini getirir veya ayarlar. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Karmaşık betik yazı tipini getirir veya ayarlar. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Karmaşık betik yazı tipini getirir veya ayarlar. |
| [getScriptFontMap()](#getScriptFontMap--) | Sunumda bulunan tüm betik yazı tipi tanımlarının bir sözlüğünü döndürür. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Sunum temasından belirli bir betik etiketiyle ilişkili yazı tipi adını alır. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Belirli bir betik etiketine yazı tipi adı atar; bu, betiğin sunumda nasıl render edileceğini tanımlar. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Temanın yazı tipi koleksiyonundan belirli bir betik etiketiyle ilişkili yazı tipi ayarını kaldırır. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Latin yazı tipini getirir veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Latin yazı tipini getirir veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Doğu Asya yazı tipini getirir veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Doğu Asya yazı tipini getirir veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Karmaşık betik yazı tipini getirir veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Karmaşık betik yazı tipini getirir veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Sunumda bulunan tüm betik yazı tipi tanımlarının bir sözlüğünü döndürür.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Betik kodlarını yazı tipi adlarıyla eşleyen bir sözlük.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Sunum temasından belirli bir betik etiketiyle ilişkili yazı tipi adını alır.

--------------------

> ```
> Bu örnek, sunum temasındaki Kiril alfabesine atanmış yazı tipini nasıl alacağınızı gösterir.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | java.lang.String | BCP-47 betik kodu (ör. "Latn", "Cyrl", "Jpan") yazı sistemini tanımlamak için kullanılır. |

**Döndürür:**
java.lang.String - Belirtilen betik için kullanılan yazı tipi adı ya da betik tanımlı değilse  null .
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Belirli bir betik etiketine yazı tipi adı atar; bu, betiğin sunumda nasıl render edileceğini tanımlar.

--------------------

> ```
> Bu örnek, Arap alfabesi için yazı tipini "Segoe UI" olarak nasıl ayarlayacağınızı gösterir:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Yazı sistemini tanımlayan BCP-47 betik kodu (ör. "Arab", "Hebr", "Hans"). |
| fontName | java.lang.String | Belirtilen betik için atanacak yazı tipi adı. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Temanın yazı tipi koleksiyonundan belirli bir betik etiketiyle ilişkili yazı tipi ayarını kaldırır.

--------------------

> ```
> Bu örnek, İbranice alfabesi için yazı tipi eşlemesini nasıl kaldıracağınızı gösterir:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Kaldırılması gereken yazı tipi ayarına sahip BCP-47 betik kodu. |