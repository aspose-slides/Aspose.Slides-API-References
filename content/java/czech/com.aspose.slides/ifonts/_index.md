---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje kolekci fontů.
type: docs
url: /cs/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Reprezentuje kolekci fontů.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Vrací nebo nastavuje latinský font. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje latinský font. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací nebo nastavuje východoasijský font. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje východoasijský font. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací nebo nastavuje font složitého skriptu. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje font složitého skriptu. |
| [getScriptFontMap()](#getScriptFontMap--) | Vrací slovník všech definic fontů skriptů v prezentaci. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Získává název fontu spojený s konkrétním skriptovým tagem z motivu prezentace. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Přiřazuje název fontu ke konkrétnímu skriptovému tagu, který určuje, jak bude text tohoto skriptu v prezentaci vykreslen. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Odstraňuje nastavení fontu spojené s konkrétním skriptovým tagem ze sbírky fontů motivu. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Vrací nebo nastavuje latinský font. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


Vrací nebo nastavuje latinský font. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Vrací nebo nastavuje východoasijský font. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


Vrací nebo nastavuje východoasijský font. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Vrací nebo nastavuje font složitého skriptu. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Vrací nebo nastavuje font složitého skriptu. Číst/Zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Vrací slovník všech definic fontů skriptů v prezentaci.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Slovník mapující kódy skriptů na názvy fontů.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


Získává název fontu spojený s konkrétním skriptovým tagem z motivu prezentace.

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
java.lang.String - Název fontu použitý pro určený skript, nebo  null  pokud skript není definován.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


Přiřazuje název fontu ke konkrétnímu skriptovému tagu, který určuje, jak bude text tohoto skriptu v prezentaci vykreslen.

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
| fontName | java.lang.String | Název fontu, který bude přiřazen určenému skriptu. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


Odstraňuje nastavení fontu spojené s konkrétním skriptovým tagem ze sbírky fontů motivu.

--------------------

> ```
> Tento příklad ukazuje, jak odstranit mapování fontu pro hebrejský skript:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| script | java.lang.String | Kód skriptu BCP-47, jehož nastavení fontu má být odstraněno. |