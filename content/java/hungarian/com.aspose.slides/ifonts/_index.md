---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: A betűkészletek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ifonts/
---```
public interface IFonts
```

A betűkészletek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Visszaadja vagy beállítja a Latin betűtípust. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a Latin betűtípust. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja vagy beállítja a Kelet-ázsiai betűtípust. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a Kelet-ázsiai betűtípust. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja vagy beállítja a komplex írásrendszer betűtípusát. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a komplex írásrendszer betűtípusát. |
| [getScriptFontMap()](#getScriptFontMap--) | Visszaad egy szótárt az összes szkript betűtípusdefinícióról a prezentációban. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Lekéri a betűtípus nevét, amely egy adott szkript címkéhez tartozik a prezentáció témájában. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Hozzárendel egy betűtípus nevet egy adott szkript címkéhez, amely meghatározza, hogyan jelenik meg a szkript szövege a prezentációban. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Eltávolítja a betűtípus beállítást, amely egy adott szkript címkéhez kapcsolódik a téma betűtípusgyűjteményéből. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Visszaadja vagy beállítja a Latin betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Visszaadja vagy beállítja a Latin betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Visszaadja vagy beállítja a Kelet-ázsiai betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Visszaadja vagy beállítja a Kelet-ázsiai betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Visszaadja vagy beállítja a komplex írásrendszer betűtípusát. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Visszaadja vagy beállítja a komplex írásrendszer betűtípusát. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Visszaad egy szótárt az összes szkript betűtípusdefinícióról a prezentációban.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Visszatér:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Egy szótár, amely a szkriptkódokat a betűtípus nevének megfelelteti.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Lekéri a betűtípus nevét, amely egy adott szkript címkéhez tartozik a prezentáció témájában.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | java.lang.String | A BCP-47 szkriptkód (pl. "Latn", "Cyrl", "Jpan"), amely egy írásrendszert azonosít. |

**Visszatér:**
java.lang.String - A megadott szkripthez használt betűtípus neve, vagy null, ha a szkript nincs definiálva.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Hozzárendel egy betűtípus nevet egy adott szkript címkéhez, amely meghatározza, hogyan jelenik meg a szkript szövege a prezentációban.

--------------------

> ```
> Ez a példa azt mutatja, hogyan állítsuk be a betűtípust az arab szkripthez "Segoe UI" értékre:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | java.lang.String | A BCP-47 szkriptkód (pl. "Arab", "Hebr", "Hans"), amely az írásrendszert azonosítja. |
| fontName | java.lang.String | A betűtípus neve, amelyet a megadott szkripthez rendelünk. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Eltávolítja a betűtípus beállítást, amely egy adott szkript címkéhez kapcsolódik a téma betűtípusgyűjteményéből.

--------------------

> ```
> Ez a példa azt mutatja, hogyan távolítható el a héber szkript betűtípus leképezése:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | java.lang.String | A BCP-47 szkriptkód, amelynek a betűtípus beállítását el szeretnénk távolítani. |