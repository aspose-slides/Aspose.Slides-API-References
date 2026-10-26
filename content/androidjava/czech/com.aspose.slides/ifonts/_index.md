---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Represents fonts collection.
type: docs
url: /cs/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Reprezentuje kolekci písem.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Vrací nebo nastavuje latinské písmo. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje latinské písmo. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací nebo nastavuje východoasijské písmo. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje východoasijské písmo. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací nebo nastavuje komplexní skript písmo. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje komplexní skript písmo. |
| [getScriptFontMap()](#getScriptFontMap--) | Vrací slovník všech definic písem skriptů v prezentaci. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Získává název písma spojený s konkrétní značkou skriptu z motivu prezentace. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Přiřadí název písma konkrétní značce skriptu, která určuje, jak bude text tohoto skriptu v prezentaci vykreslen. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Odstraňuje nastavení písma spojené s konkrétní značkou skriptu ze sbírky písem motivu. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Vrací nebo nastavuje latinské písmo. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


Vrací nebo nastavuje latinské písmo. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Vrací nebo nastavuje východoasijské písmo. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


Vrací nebo nastavuje východoasijské písmo. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Vrací nebo nastavuje komplexní skript písmo. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Vrací nebo nastavuje komplexní skript písmo. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Vrací slovník všech definic písem skriptů v prezentaci.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Vrací:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Slovník mapující kódy skriptů na názvy písem.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


Získává název písma spojený s konkrétní značkou skriptu z motivu prezentace.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| script | java.lang.String | Kód skriptu BCP-47 (např. "Latn", "Cyrl", "Jpan") používaný k identifikaci psacího systému. |

**Vrací:**
java.lang.String - Název písma použitého pro zadaný skript, nebo null, pokud skript není definován.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


Přiřadí název písma konkrétní značce skriptu, která určuje, jak bude text tohoto skriptu v prezentaci vykreslen.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| script | java.lang.String | Kód skriptu BCP-47 (např. "Arab", "Hebr", "Hans") identifikující psací systém. |
| fontName | java.lang.String | Název písma, který má být přiřazen k zadanému skriptu. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


Odstraňuje nastavení písma spojené s konkrétní značkou skriptu ze sbírky písem motivu.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| script | java.lang.String | Kód skriptu BCP-47, jehož nastavení písma má být odstraněno. |