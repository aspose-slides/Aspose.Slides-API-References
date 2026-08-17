---
title: FontFallBackRule
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Schriftart-Fallback-Regel dar
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

Stellt die Schriftart-FallBack-Regel dar
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Erstellt eine neue Instanz. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Erstellt eine neue Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Fügt neue Schriftart(en) zur Liste der FallBack-Schriftarten hinzu. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Fügt neue Schriftart(en) zur Liste der FallBack-Schriftarten hinzu. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Liefert den ersten Index eines kontinuierlichen Unicode-Bereichs. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Liefert den ersten Index eines kontinuierlichen Unicode-Bereichs. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Liefert den letzten Index eines kontinuierlichen Unicode-Bereichs. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Liefert den letzten Index eines kontinuierlichen Unicode-Bereichs. |
| [getCount()](#getCount--) | Ermittelt die Anzahl der tatsächlich für den Bereich definierten Schriftarten. |
| [get_Item(int index)](#get-Item-int-) | Ermittelt den Schriftartnamen am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Schriftarten aus der Liste. |
| [remove(String fontName)](#remove-java.lang.String-) | Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die FallBack-Schriftart am angegebenen Index der Liste. |
| [toArray()](#toArray--) | Erstellt und liefert ein Array mit allen FallBack-Schriftarten für diese Regel. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und liefert ein Array mit allen FallBack-Schriftarten aus dem angegebenen Bereich in der Liste. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Liefert den Index der angegebenen Regel in der Sammlung. |
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
| fontNames | java.lang.String | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |

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
| fontNames | java.lang.String[] | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Fügt neue Schriftart(en) zur Liste der FallBack-Schriftarten hinzu.

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
| fontName | java.lang.String | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Fügt neue Schriftart(en) zur Liste der FallBack-Schriftarten hinzu.

--------------------

> ```
> //Erstelle neue Instanz von FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Füge weitere drei Schriftarten zur Regel hinzu 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontNames | java.lang.String[] | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Liefert den ersten Index eines kontinuierlichen Unicode-Bereichs.

**Rückgabe:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Liefert den ersten Index eines kontinuierlichen Unicode-Bereichs.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Liefert den letzten Index eines kontinuierlichen Unicode-Bereichs.

**Rückgabe:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Liefert den letzten Index eines kontinuierlichen Unicode-Bereichs.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Ermittelt die Anzahl der tatsächlich für den Bereich definierten Schriftarten. Nur lesbarer int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Ermittelt den Schriftartnamen am angegebenen Index. Nur lesbar [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

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


Entfernt alle Schriftarten aus der Liste.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste.

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
| fontName | java.lang.String | Der zu entfernende Schriftartname. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt die FallBack-Schriftart am angegebenen Index der Liste.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Entferne Tahoma aus der Liste.
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


Erstellt und liefert ein Array mit allen FallBack-Schriftarten für diese Regel.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Erhalte alle Schriftartnamen als Array.
>  String[] fontNames = newRule.toArray();
> ```

**Rückgabe:**
java.lang.String[] - Array von String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Erstellt und liefert ein Array mit allen FallBack-Schriftarten aus dem angegebenen Bereich in der Liste.

```
// Erstelle eine Regel, die eine Liste von Schriftarten enthält.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Erhalte die letzten beiden Schriftartnamen als Array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Index der ersten hinzuzufügenden Schriftart. |
| count | int | Anzahl der hinzuzufügenden Schriftarten. |

**Rückgabe:**
java.lang.String[] - Array von String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Liefert den Index der angegebenen Regel in der Sammlung.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Erhalte Index von Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Zu findender Schriftartname. |

**Rückgabe:**
int - Index einer Schriftart oder -1, falls die Schriftart nicht in der Liste gefunden wurde.