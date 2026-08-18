---
title: Fonts
second_title: Aspose.Slides for Java API Referansı
description: Yazı tipleri koleksiyonu.
type: docs
url: /tr/com.aspose.slides/fonts/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Yazı tipleri koleksiyonu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Sunumda bulunan tüm betik yazı tipi tanımlarının sözlüğünü döndürür. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Sunum temasından belirli bir betik etiketine ilişkili yazı tipi adını alır. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Belirli bir betik etiketine bir yazı tipi adı atar; bu, o betiğin sunumda nasıl render edileceğini tanımlar. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Temanın yazı tipi koleksiyonundan belirli bir betik etiketine ilişkili yazı tipi ayarını kaldırır. |
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

Sunumda bulunan tüm betik yazı tipi tanımlarının sözlüğünü döndürür.

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

Sunum temasından belirli bir betik etiketiyle ilişkili yazı tipi adını alır.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Bir yazı sistemini tanımlamak için kullanılan BCP-47 betik kodu (ör. "Latn", "Cyrl", "Jpan"). |

**Döndürür:**
java.lang.String - Belirtilen betik için kullanılan yazı tipi adı, betik tanımlı değilse  null  döndürür.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Belirli bir betik etiketine bir yazı tipi adı atar; bu, o betiğin sunumda nasıl görüntüleneceğini tanımlar.

--------------------

> ```
> Bu örnek, Arap betiği için yazı tipini "Segoe UI" olarak ayarlamayı gösterir:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Bir yazı sistemini tanımlamak için kullanılan BCP-47 betik kodu (ör. "Arab", "Hebr", "Hans"). |
| fontName | java.lang.String | Belirtilen betiğe atanacak yazı tipi adı. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Temanın yazı tipi koleksiyonundan belirli bir betik etiketiyle ilişkili yazı tipi ayarını kaldırır.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| script | java.lang.String | Kaldırılması gereken betik kodu. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Latin yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Latin yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Doğu Asya yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Doğu Asya yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Karmaşık betik yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Karmaşık betik yazı tipini döndürür veya ayarlar. Okunur/yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |