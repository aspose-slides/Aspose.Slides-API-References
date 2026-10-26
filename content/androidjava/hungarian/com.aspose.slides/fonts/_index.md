---
title: Fonts
second_title: Aspose.Slides for Android Java API hivatkozás
description: Betűtípus-gyűjtemény.
type: docs
url: /hu/com.aspose.slides/fonts/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Betűtípusgyűjtemény.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Visszaad egy szótárt az összes szkriptbetűtípus-definícióról a bemutatóban. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Lekéri a betűtípus nevét, amely egy adott szkriptcímkéhez van társítva a bemutató témájából. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Hozzárendel egy betűtípusnevet egy adott szkriptcímkéhez, amely meghatározza, hogyan lesz a szkript szövege megjelenítve a bemutatóban. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Eltávolítja a betűtípus beállítást, amely egy adott szkriptcímkéhez van társítva a téma betűtípus-gyűjteményéből. |
| [getLatinFont()](#getLatinFont--) | Visszaadja vagy beállítja a latin betűtípust. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a latin betűtípust. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja vagy beállítja a kelet-ázsiai betűtípust. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a kelet-ázsiai betűtípust. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja vagy beállítja a komplex szkript betűtípust. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a komplex szkript betűtípust. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Visszaad egy szótárt az összes szkriptbetűtípus-definícióról a bemutatóban.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - A szótár a szkriptkódokat betűtípus-nevekre képezi le.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

Lekéri a betűtípus nevét, amely egy adott szkriptcímkéhez van társítva a bemutató témájából.

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
| script | java.lang.String | A BCP-47 szkriptkód (például „Latn”, „Cyrl”, „Jpan”) a írásrendszer azonosításához használt. |

**Visszatér:**
java.lang.String – A megadott szkripthez használt betűtípus neve, vagy  null  ha a szkript nincs definiálva.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Hozzárendel egy betűtípusnevet egy adott szkriptcímkéhez, amely meghatározza, hogyan lesz a szkript szövege megjelenítve a bemutatóban.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | java.lang.String | A BCP-47 szkriptkód (például „Arab”, „Hebr”, „Hans”) a írásrendszer azonosításához. |
| fontName | java.lang.String | A betűtípus neve, amelyet a megadott szkriptnek kell hozzárendelni. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Eltávolítja a betűtípus beállítást, amely egy adott szkriptcímkéhez van társítva a téma betűtípus-gyűjteményéből.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | java.lang.String | A BCP-47 szkriptkód, amelynek a betűtípusbeállítását el kell távolítani. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Visszaadja vagy beállítja a latin betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Visszaadja vagy beállítja a latin betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Visszaadja vagy beállítja a kelet-ázsiai betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Visszaadja vagy beállítja a kelet-ázsiai betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Visszaadja vagy beállítja a komplex szkript betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Visszaadja vagy beállítja a komplex szkript betűtípust. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |