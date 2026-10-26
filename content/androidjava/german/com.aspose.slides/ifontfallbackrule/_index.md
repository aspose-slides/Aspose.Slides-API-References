---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Represents font fallback rule
type: docs
url: /de/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Stellt die Schriftart-Fallback-Regel dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Fügt ein(e) neue(s) Schriftart(en) zur Liste der FallBack-Schriftarten hinzu. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Fügt neue Schriftarten zur Liste der FallBack-Schriftarten hinzu. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Gibt den ersten Index des zusammenhängenden Unicode-Bereichs zurück. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Gibt den letzten Index des zusammenhängenden Unicode-Bereichs zurück. |
| [getCount()](#getCount--) | Gibt die Anzahl der tatsächlich für den Bereich definierten Schriftarten zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt den Schriftartnamen am angegebenen Index zurück. |
| [clear()](#clear--) | Entfernt alle Schriftarten aus der Liste. |
| [remove(String fontName)](#remove-java.lang.String-) | Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die FallBack-Schriftart am angegebenen Index der Liste. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array mit allen FallBack-Schriftarten für diese Regel zurück. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array mit allen FallBack-Schriftarten aus dem angegebenen Bereich in der Liste zurück. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Gibt den Index der angegebenen Regel in der Sammlung zurück. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


Fügt ein(e) neue(s) Schriftart(en) zur Liste der FallBack-Schriftarten hinzu.

--------------------

> ```
> //Erstelle eine neue Instanz von FantFallBackRule
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
public abstract void addFallBackFonts(String[] fontNames)
```


Fügt neue Schriftarten zur Liste der FallBack-Schriftarten hinzu.

--------------------

> ```
> //Erstelle eine neue Instanz von FontFallBackRule
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
public abstract long getRangeStartIndex()
```


Gibt den ersten Index des zusammenhängenden Unicode-Bereichs zurück.

**Rückgabe:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```


Gibt den letzten Index des zusammenhängenden Unicode-Bereichs zurück.

**Rückgabe:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gibt die Anzahl der tatsächlich für den Bereich definierten Schriftarten zurück.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```


Gibt den Schriftartnamen am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Schriftarten aus der Liste.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```


Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Entfernen von Tahoma aus der Liste
>  newRule.remove("Tahoma");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Der Name der zu entfernenden Schriftart. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt die FallBack-Schriftart am angegebenen Index der Liste.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Entfernen von Tahoma aus der Liste
>  newRule.remove(2);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index der zu entfernenden Schriftart. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```


Erstellt und gibt ein Array mit allen FallBack-Schriftarten für diese Regel zurück.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Hole alle Schriftartnamen als Array
>  String[] fontNames = newRule.toArray();
> ```

**Rückgabe:**
java.lang.String[] - Array von String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


Erstellt und gibt ein Array mit allen FallBack-Schriftarten aus dem angegebenen Bereich in der Liste zurück.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Erhalte die letzten beiden Schriftartnamen als Array
>  String[] fontNames = newRule.toArray(2,2);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Der Index der ersten hinzuzufügenden Schriftart. |
| count | int | Die Anzahl der hinzuzufügenden Schriftarten. |

**Rückgabe:**
java.lang.String[] - Array von String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```


Gibt den Index der angegebenen Regel in der Sammlung zurück.

--------------------

> ```
> // Erstelle eine Regel, die eine Liste von Schriftarten enthält.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Erhalte den Index von Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Gesuchte Schriftart. |

**Rückgabe:**
int - Index einer Schriftart oder -1, wenn die Schriftart nicht in der Liste gefunden wurde.