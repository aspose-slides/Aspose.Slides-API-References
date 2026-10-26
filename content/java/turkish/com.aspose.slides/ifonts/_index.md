---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Represents fonts collection.
type: docs
url: /tr/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Yazı tipleri koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Latin yazı tipini döndürür veya ayarlar. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin yazı tipini döndürür veya ayarlar. |
| [getEastAsianFont()](#getEastAsianFont--) | East Asian yazı tipini döndürür veya ayarlar. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | East Asian yazı tipini döndürür veya ayarlar. |
| [getComplexScriptFont()](#getComplexScriptFont--) | complex script yazı tipini döndürür veya ayarlar. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | complex script yazı tipini döndürür veya ayarlar. |
| [getScriptFontMap()](#getScriptFontMap--) | Sunumda tüm script yazı tipi tanımlarının bir sözlüğünü döndürür. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Sunum temasından belirli bir script etiketine ilişkili yazı tipi adını alır. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Belirli bir script etiketine bir yazı tipi adı atar; bu, o scriptin metninin sunumda nasıl render edileceğini tanımlar. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Tema'nın yazı tipi koleksiyonundan belirli bir script etiketine ilişkili yazı tipi ayarını kaldırır. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Latin yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Latin yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

East Asian yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

East Asian yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

complex script yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

complex script yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Sunumda tüm script yazı tipi tanımlarının bir sözlüğünü döndürür.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - script kodlarını yazı tipi adlarına eşleyen bir sözlük.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Sunum temasından belirli bir script etiketine ilişkili yazı tipi adını alır.

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
| script | java.lang.String | Yazı sistemini tanımlamak için kullanılan BCP-47 script kodu (ör. "Latn", "Cyrl", "Jpan"). |

**Döndürür:**
java.lang.String - Belirtilen script için kullanılan yazı tipi adı, script tanımlı değilse  null  olarak döner.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Belirli bir script etiketine bir yazı tipi adı atar; bu, o scriptin metninin sunumda nasıl render edileceğini tanımlar.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Yazı sistemini tanımlayan BCP-47 script kodu (ör. "Arab", "Hebr", "Hans"). |
| fontName | java.lang.String | Belirtilen script için atanacak yazı tipi adı. |
### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Tema'nın yazı tipi koleksiyonundan belirli bir script etiketine ilişkili yazı tipi ayarını kaldırır.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Kaldırılması gereken yazı tipi ayarının BCP-47 script kodu. |