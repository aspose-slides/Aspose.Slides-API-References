---
title: Fonts
second_title: Aspose.Slides pro Android přes Java API Reference
description: Kolekce písem.
type: docs
url: /cs/com.aspose.slides/fonts/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Kolekce písem.
## Metody

| Metoda | Popis |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Vrací slovník všech definic písem pro jednotlivé skripty v prezentaci. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Získává název písma spojený s konkrétní značkou skriptu v motivu prezentace. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Přiřadí název písma ke konkrétní značce skriptu, což určuje, jak bude text tohoto skriptu v prezentaci vykreslen. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Odstraňuje nastavení písma spojené s konkrétní značkou skriptu z kolekce písem motivu. |
| [getLatinFont()](#getLatinFont--) | Vrací nebo nastavuje latinské písmo. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje latinské písmo. |
| [getEastAsianFont()](#getEastAsianFont--) | Vrací nebo nastavuje východoasijské písmo. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje východoasijské písmo. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Vrací nebo nastavuje písmo komplexního skriptu. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje písmo komplexního skriptu. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Vrací slovník všech definic písem pro jednotlivé skripty v prezentaci.

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
public final String getScriptFont(String script)
```


Získává název písma spojený s konkrétní značkou skriptu v motivu prezentace.

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
| script | java.lang.String | Kód skriptu BCP-47 (e.g., "Latn", "Cyrl", "Jpan") používaný k identifikaci systému psaní. |

**Vrací:**
java.lang.String - Název písma použitého pro zadaný skript, nebo  null  pokud skript není definován.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


Přiřadí název písma ke konkrétní značce skriptu, což určuje, jak bude text tohoto skriptu v prezentaci vykreslen.

--------------------

> ```
> Tento příklad ukazuje, jak nastavit písmo pro arabský skript na "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| script | java.lang.String | Kód skriptu BCP-47 (e.g., "Arab", "Hebr", "Hans") identifikující systém psaní. |
| fontName | java.lang.String | Název písma, které má být přiřazeno ke konkrétnímu skriptu. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


Odstraňuje nastavení písma spojené s konkrétní značkou skriptu z kolekce písem motivu.

--------------------

> ```
> Tento příklad ukazuje, jak odstranit mapování písma pro hebrejský skript:
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


Vrací nebo nastavuje latinské písmo. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


Vrací nebo nastavuje latinské písmo. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


Vrací nebo nastavuje východoasijské písmo. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


Vrací nebo nastavuje východoasijské písmo. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


Vrací nebo nastavuje písmo komplexního skriptu. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


Vrací nebo nastavuje písmo komplexního skriptu. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  

