---
title: FontFallBackRule
second_title: Aspose.Slides for Java API Referenciája
description: A betűtípus visszaesési szabályt reprezentálja
type: docs
url: /hu/com.aspose.slides/fontfallbackrule/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

A betűkészlet tartalék szabályát reprezentálja
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Új példányt hoz létre. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Új példányt hoz létre. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Új betűt (betűket) ad hozzá a FallBack betűk listájához. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Új betűket ad hozzá a FallBack betűk listájához. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Lekérdezi a folyamatos Unicode tartomány első indexét. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Lekérdezi a folyamatos Unicode tartomány első indexét. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Lekérdezi a folyamatos Unicode tartomány utolsó indexét. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Lekérdezi a folyamatos Unicode tartomány utolsó indexét. |
| [getCount()](#getCount--) | Lekérdezi a tartományhoz ténylegesen definiált betűk számát. |
| [get_Item(int index)](#get-Item-int-) | Lekérdezi a megadott indexnél lévő betű nevét. |
| [clear()](#clear--) | Eltávolítja az összes betűt a listából. |
| [remove(String fontName)](#remove-java.lang.String-) | Eltávolítja a listából egy adott FallBack betű első előfordulását. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a listában a megadott indexnél lévő FallBack betűt. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt az összes FallBack betűvel ehhez a szabályhoz. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt az összes FallBack betűvel a listában a megadott tartományból. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Visszaadja a megadott szabály indexét a gyűjteményben. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

Új példányt hoz létre.

--------------------

> ```
> // Hozzon létre egy új FantFallBackRule példányt egy betűtípussal.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Hozzon létre egy új FantFallBackRule példányt több betűtípussal.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | long | Unicode tartomány kezdő indexe |
| endIndex | long | Unicode tartomány befejező indexe |
| fontNames | java.lang.String | A FallBack-hez betű neve vagy nevei (vesszővel elválasztva) |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Új példányt hoz létre.

--------------------

> ```
> // Hozzon létre egy új FantFallBackRule példányt két betűtípussal
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Hozzon létre egy új FantFallBackRule példányt több betűtípussal.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | long | Unicode tartomány kezdő indexe |
| endIndex | long | Unicode tartomány befejező indexe |
| fontNames | java.lang.String[] | A FallBack-hez betű neve vagy nevei (vesszővel elválasztva) |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Új betűt (betűket) ad hozzá a FallBack betűk listájához.

--------------------

> ```
> // Hozzon létre egy új FontFallBackRule példányt
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Adjon hozzá egy második betűtípust a szabályhoz 
>  newRule.addFallBackFonts("MS Gothic");
>  //Adjon hozzá egy harmadik és negyedik betűtípust a szabályhoz 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A FallBack-hez betű neve vagy nevei (vesszővel elválasztva) |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

Új betűket ad hozzá a FallBack betűk listájához.

--------------------

> ```
> //Hozzon létre egy új FontFallBackRule példányt
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Adjon hozzá további három betűtípust a szabályhoz 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontNames | java.lang.String[] | A FallBack-hez betű neve vagy nevei (vesszővel elválasztva) |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

Lekérdezi a folyamatos Unicode tartomány első indexét.

**Visszatérési érték:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

Lekérdezi a folyamatos Unicode tartomány első indexét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

Lekérdezi a folyamatos Unicode tartomány utolsó indexét.

**Visszatérési érték:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

Lekérdezi a folyamatos Unicode tartomány utolsó indexét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

Lekérdezi a tartományhoz ténylegesen definiált betűk számát. Csak olvasható int.

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

Lekérdezi a megadott indexnél lévő betű nevét. Csak olvasható [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes betűt a listából.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Eltávolítja a listából egy adott FallBack betű első előfordulását.

--------------------

> ```
> // Hozzon létre egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Távolítsa el a Tahoma betűtípust a listáról.
>  newRule.remove("Tahoma");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A listából eltávolítandó betű neve. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a listában a megadott indexnél lévő FallBack betűt.

--------------------

> ```
> // Hozzon létre egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma eltávolítása a listáról.
>  newRule.remove(2);
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A betű eltávolításához használandó nulláról induló index. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

Létrehoz és visszaad egy tömböt az összes FallBack betűvel ehhez a szabályhoz.

--------------------

> ```
> // Hozzon létre egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Az összes betűtípus nevet tömbként kapja meg.
>  String[] fontNames = newRule.toArray();
```

**Visszatérési érték:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt az összes FallBack betűvel a listában a megadott tartományból.

```
// Hozzon létre egy szabályt, amely betűtípusok listáját tartalmazza.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Az utolsó két betűtípus nevét tömbként kapja meg.
 String[] fontNames = newRule.toArray(2, 2);
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | A hozzáadandó első betű indexe. |
| count | int | A hozzáadandó betűk száma. |

**Visszatérési érték:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

Visszaadja a megadott szabály indexét a gyűjteményben.

--------------------

> ```
> // Hozzon létre egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // A Tahoma indexét kapja meg.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A megtalálandó betű neve. |

**Visszatérési érték:**
int - Index of a font or -1 if font not found in list.