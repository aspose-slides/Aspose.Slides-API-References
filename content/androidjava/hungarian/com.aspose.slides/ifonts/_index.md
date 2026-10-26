---
title: IFonts
second_title: Aspose.Slides for Android Java API Referencia
description: A betűtípus-gyűjteményt reprezentálja.
type: docs
url: /hu/com.aspose.slides/ifonts/
---```
public interface IFonts
```

A betűtípus-gyűjteményt reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Visszaadja vagy beállítja a Latin betűtípust. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a Latin betűtípust. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja vagy beállítja a Kelet-ázsiai betűtípust. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a Kelet-ázsiai betűtípust. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja vagy beállítja a komplex szkript betűtípust. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a komplex szkript betűtípust. |
| [getScriptFontMap()](#getScriptFontMap--) | Visszaad egy szótárat a prezentáció összes szkript betűtípus-definíciójával. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Lekéri egy adott szkriptcímkéhez tartozó betűtípus nevét a prezentáció témájából. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Egy betűtípus nevet ad egy adott szkriptcímkéhez, amely meghatározza, hogyan jelenik meg a szkript szövege a prezentációban. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Eltávolítja az adott szkriptcímkéhez kapcsolódó betűtípusbeállítást a téma betűtípus-gyűjteményéből. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Visszaadja vagy beállítja a Latin betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
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

**Visszatérési érték:**
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


Visszaadja vagy beállítja a komplex szkript betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatérési érték:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Visszaadja vagy beállítja a komplex szkript betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Visszaad egy szótárat a prezentáció összes szkript betűtípus-definíciójával.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Egy szótár, amely a szkriptkódokat betűtípusnevekkel térképezi fel.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


Lekéri egy adott szkriptcímkéhez tartozó betűtípus nevét a prezentáció témájából.

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
| script | java.lang.String | A BCP-47 szkriptkód (pl. "Latn", "Cyrl", "Jpan"), amely a írásrendszert azonosítja. |

**Visszatérési érték:**
java.lang.String - A megadott szkripthez használt betűtípus neve, vagy  null  ha a szkript nincs definiálva.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


Egy betűtípus nevet ad egy adott szkriptcímkéhez, amely meghatározza, hogyan jelenik meg a szkript szövege a prezentációban.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | java.lang.String | A BCP-47 szkriptkód (pl. "Arab", "Hebr", "Hans"), amely az írásrendszert azonosítja. |
| fontName | java.lang.String | A megadott szkripthez rendelendő betűtípus neve. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


Eltávolítja az adott szkriptcímkéhez kapcsolódó betűtípus-beállítást a téma betűtípus-gyűjteményéből.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | java.lang.String | A BCP-47 szkriptkód, amelynek betűtípus-beállítását el kell távolítani. |