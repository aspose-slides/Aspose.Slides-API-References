---
title: Fonts
second_title: Aspose.Slides a Java API referenciája
description: Betűtípusok gyűjteménye.
type: docs
url: /hu/com.aspose.slides/fonts/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Betűtípusok gyűjteménye.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Visszaad egy szótárt, amely a prezentációban található összes írásrendszer-betűtípus definíciót tartalmaz. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Lekéri a prezentáció témájából egy adott írásrendszer címkéjéhez tartozó betűtípus-nevet. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Egy betűtípus-nevet rendel egy adott írásrendszer címkéjéhez, amely meghatározza, hogyan jelenik meg a szöveg a prezentációban. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Eltávolítja az adott írásrendszer címkéjéhez tartozó betűtípus-beállítást a téma betűtípus-gyűjteményéből. |
| [getLatinFont()](#getLatinFont--) | Visszaadja vagy beállítja a latin betűtípust. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a latin betűtípust. |
| [getEastAsianFont()](#getEastAsianFont--) | Visszaadja vagy beállítja a kelet-ázsiai betűtípust. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a kelet-ázsiai betűtípust. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Visszaadja vagy beállítja a komplex írás betűtípusát. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Visszaadja vagy beállítja a komplex írás betűtípusát. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Visszaad egy szótárt, amely a prezentációban található összes írásrendszer-betűtípus definíciót tartalmaz.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Egy szótár, amely a szkriptkódokat a betűtípus-nevekre térképezi.

### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

Lekéri a prezentáció témájából egy adott írásrendszer címkéjéhez tartozó betűtípus-nevet.

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
| script | java.lang.String | A BCP-47 írásrendszer-kód (például „Latn”, „Cyrl”, „Jpan”), amely a írásrendszert azonosítja. |

**Visszatér:**
java.lang.String - A megadott írásrendszerhez használt betűtípus neve, vagy  null  ha az írásrendszer nincs definiálva.

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Egy betűtípus-nevet rendel egy adott írásrendszer címkéjéhez, amely meghatározza, hogyan jelenik meg az adott írásrendszer szövege a prezentációban.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | java.lang.String | A BCP-47 írásrendszer-kód (például „Arab”, „Hebr”, „Hans”), amely az írásrendszert azonosítja. |
| fontName | java.lang.String | A betűtípus neve, amelyet a megadott írásrendszerhez rendel. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Eltávolítja az adott írásrendszer címkéjéhez tartozó betűtípus-beállítást a téma betűtípus-gyűjteményéből.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | java.lang.String | A BCP-47 írásrendszer-kód, amelynek betűtípus-beállítását el kell távolítani. |

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

Visszaadja vagy beállítja a komplex írás betűtípusát. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Visszaadja vagy beállítja a komplex írás betűtípusát. Olvasás/írás [IFontData](../../com.aspose.slides/ifontdata).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |