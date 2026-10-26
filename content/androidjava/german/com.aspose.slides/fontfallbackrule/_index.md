---
title: FontFallBackRule
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Schriftart-Fallback-Regel dar
type: docs
url: /de/com.aspose.slides/fontfallbackrule/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Stellt eine Schriftart-Fallback-Regel dar
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Erstellt eine neue Instanz. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Erstellt eine neue Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Fügt ein(e) neue(s) Schriftart(en) zur Liste der FallBack-Schriften hinzu. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Fügt neue Schriften zur Liste der FallBack-Schriften hinzu. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Gibt den ersten Index des zusammenhängenden Unicode-Bereichs zurück. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Gibt den ersten Index des zusammenhängenden Unicode-Bereichs zurück. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Gibt den letzten Index des zusammenhängenden Unicode-Bereichs zurück. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Gibt den letzten Index des zusammenhängenden Unicode-Bereichs zurück. |
| [getCount()](#getCount--) | Gibt die tatsächlich für den Bereich definierten Schriften zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt den Schriftartnamen am angegebenen Index zurück. |
| [clear()](#clear--) | Entfernt alle Schriften aus der Liste. |
| [remove(String fontName)](#remove-java.lang.String-) | Entfernt das erste Vorkommen einer bestimmten FallBack-Schrift aus der Liste. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die FallBack-Schrift am angegebenen Index der Liste. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array mit allen FallBack-Schriften für diese Regel zurück. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array mit allen FallBack-Schriften aus dem angegebenen Bereich in der Liste zurück. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Gibt den Index der angegebenen Regel in der Sammlung zurück. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

Erstellt eine neue Instanz.

--------------------

> ```
> // Erstelle neue Instanz von FantFallBackRule mit einer Schriftart.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Erstelle neue Instanz von FantFallBackRule mit mehreren Schriftarten.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | long | Startindex des Unicode-Bereichs |
| endIndex | long | Endindex des Unicode-Bereichs |
| fontNames | java.lang.String | Name bzw. Namen der Schriftart (durch Komma getrennt) für FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Erstellt eine neue Instanz.

--------------------

> ```
> // Erstelle neue Instanz von FantFallBackRule mit zwei Schriftarten
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Erstelle neue Instanz von FantFallBackRule mit mehreren Schriftarten.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | long | Startindex des Unicode-Bereichs |
| endIndex | long | Endindex des Unicode-Bereichs |
| fontNames | java.lang.String[] | Name bzw. Namen der Schriftart (durch Komma getrennt) für FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Fügt ein(e) neue(s) Schriftart(en) zur Liste der FallBack-Schriften hinzu.

--------------------

> ```
> // Erstelle neue Instanz von FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Füge eine zweite Schriftart zur Regel hinzu 
>  newRule.addFallBackFonts("MS Gothic");
>  //Füge eine dritte und vierte Schriftart zur Regel hinzu 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Name bzw. Namen der Schriftart (durch Komma getrennt) für FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

Fügt neue Schriften zur Liste der FallBack-Schriften hinzu.

--------------------

> ```
> // Erstelle neue Instanz von FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Füge drei weitere Schriftarten zur Regel hinzu 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontNames | java.lang.String[] | Name bzw. Namen der Schriftart (durch Komma getrennt) für FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

Gibt den ersten Index des zusammenhängenden Unicode-Bereichs zurück.

**Rückgabe:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

Gibt den ersten Index des zusammenhängenden Unicode-Bereichs zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

Gibt den letzten Index des zusammenhängenden Unicode-Bereichs zurück.

**Rückgabe:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

Gibt den letzten Index des zusammenhängenden Unicode-Bereichs zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die tatsächlich für den Bereich definierten Schriften zurück. Schreibgeschützt int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

Gibt den Schriftartnamen am angegebenen Index zurück. Schreibgeschützt [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Schriften aus der Liste.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Entfernt das erste Vorkommen einer spezifischen FallBack-Schrift aus der Liste.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Entferne Tahoma aus der Liste.
>  newRule.remove("Tahoma");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Name der zu entfernenden Schriftart aus der Liste. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt die FallBack-Schrift am angegebenen Index der Liste.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Entferne Tahoma aus der Liste.
>  newRule.remove(2);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index der zu entfernenden Schriftart. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

Erstellt und gibt ein Array mit allen FallBack-Schriften für diese Regel zurück.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Hole alle Schriftartnamen als Array.
>  String[] fontNames = newRule.toArray();
> ```


**Rückgabe:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Erstellt und gibt ein Array mit allen FallBack-Schriften aus dem angegebenen Bereich in der Liste zurück.

```
// Erstelle eine Regel, die eine Liste von Schriftarten enthält.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Hole die letzten beiden Schriftartnamen als Array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Ein Index der ersten hinzuzufügenden Schriftart. |
| count | int | Eine Anzahl von hinzuzufügenden Schriften. |

**Rückgabe:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

Gibt den Index der angegebenen Regel in der Sammlung zurück.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Hole den Index von Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Name der zu findenden Schriftart. |

**Rückgabe:**
int - Index einer Schriftart oder -1, falls die Schriftart nicht in der Liste gefunden wurde.