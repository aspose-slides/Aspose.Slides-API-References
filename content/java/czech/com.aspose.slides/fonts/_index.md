---
title: Fonts
second_title: Aspose.Slides pro Java – reference API
description: Kolekce písem.
type: docs
url: /cs/com.aspose.slides/fonts/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Kolekce písem.
## Metody

| Metoda | Popis |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Vrací slovník všech definic písma skriptů v prezentaci. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Získá název písma přiřazený konkrétní skriptové značce z motivu prezentace. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Přiřadí název písma konkrétní skriptové značce, která určuje, jak bude text v tomto skriptu v prezentaci vykreslen. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Odstraní nastavení písma spojené s konkrétní skriptovou značkou ze sbírky písem motivu. |
| [getLatinFont()](#getLatinFont--) | Vrací nebo nastavuje latinské písmo. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje latinské písmo. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací nebo nastavuje východoasijské písmo. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje východoasijské písmo. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací nebo nastavuje písmo pro komplexní skripty. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje písmo pro komplexní skripty. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Vrací slovník všech definic písma skriptů v prezentaci.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**Návrat:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Slovník mapující kódy skriptů na názvy písem.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```


Získá název písma přiřazený konkrétní skriptové značce z motivu prezentace.

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

**Návrat:**
java.lang.String - Název písma použitého pro zadaný skript, nebo  null  pokud skript není definován.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


Přiřadí název písma konkrétní skriptové značce, která určuje, jak bude text v tomto skriptu v prezentaci vykreslen.

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
| fontName | java.lang.String | Název písma, které se má přiřadit ke zvolenému skriptu. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


Odstraní nastavení písma spojené s konkrétní skriptovou značkou ze sbírky písem motivu.

--------------------

> ```
> Tento příklad ukazuje, jak odstranit mapování písma pro hebrejské písmo:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| script | java.lang.String | Kód skriptu BCP-47, jehož nastavení písma má být odstraněno. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```


Vrací nebo nastavuje latinské písmo. Číst/zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Návrat:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


Vrací nebo nastavuje latinské písmo. Číst/zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


Vrací nebo nastavuje východoasijské písmo. Číst/zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Návrat:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


Vrací nebo nastavuje východoasijské písmo. Číst/zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


Vrací nebo nastavuje písmo pro komplexní skripty. Číst/zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Návrat:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


Vrací nebo nastavuje písmo pro komplexní skripty. Číst/zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |