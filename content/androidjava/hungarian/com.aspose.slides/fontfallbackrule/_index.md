---
title: FontFallBackRule
second_title: Aspose.Slides Androidra Java API hivatkozás
description: A betűtípus helyettesítési szabályt ábrázolja
type: docs
url: /hu/com.aspose.slides/fontfallbackrule/
---
**Öröklődés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

A betűtípus helyettesítési szabályt ábrázolja
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Új példányt hoz létre. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Új példányt hoz létre. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Új betűtípust (vagy betűtípusokat) ad a FallBack betűtípusok listájához. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Új betűtípusokat ad a FallBack betűtípusok listájához. |
| [getRangeStartIndex()](#getRangeStartIndex--) | A folyamatos Unicode-tartomány első indexét adja vissza. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | A folyamatos Unicode-tartomány első indexét adja vissza. |
| [getRangeEndIndex()](#getRangeEndIndex--) | A folyamatos Unicode-tartomány utolsó indexét adja vissza. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | A folyamatos Unicode-tartomány utolsó indexét adja vissza. |
| [getCount()](#getCount--) | A tartományhoz ténylegesen definiált betűtípusok számát adja vissza. |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű betűtípus nevét adja vissza. |
| [clear()](#clear--) | Eltávolítja az összes betűtípust a listáról. |
| [remove(String fontName)](#remove-java.lang.String-) | Eltávolítja egy adott FallBack betűtípus első előfordulását a listáról. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a FallBack betűtípust a lista megadott indexén. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal ehhez a szabályhoz. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal a listában a megadott tartományból. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Visszaadja a megadott szabály indexét a gyűjteményben. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

Új példányt hoz létre.

--------------------

> ```
> // Create new instance of FantFallBackRule with one font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Create new instance of FantFallBackRule with several fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | long | Unicode-tartomány kezdő indexe |
| endIndex | long | Unicode-tartomány vég indexe |
| fontNames | java.lang.String | A betűtípus neve vagy nevei (vesszővel elválasztva) a FallBack számára |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Új példányt hoz létre.

--------------------

> ```
> // Új példányt hoz létre a FantFallBackRule-ból két betűtípussal
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Új példányt hoz létre a FantFallBackRule-ból több betűtípussal.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | long | Unicode-tartomány kezdő indexe |
| endIndex | long | Unicode-tartomány vég indexe |
| fontNames | java.lang.String[] | A betűtípus neve vagy nevei (vesszővel elválasztva) a FallBack számára |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Új betűtípust (vagy betűtípusokat) ad a FallBack betűtípusok listájához.

--------------------

> ```
> // Új példányt hoz létre a FontFallBackRule-ból
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //A szabályhoz hozzáad egy második betűtípust 
>  newRule.addFallBackFonts("MS Gothic");
>  //A szabályhoz hozzáad egy harmadik és negyedik betűtípust 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A betűtípus neve vagy nevei (vesszővel elválasztva) a FallBack számára |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

Új betűtípusokat ad a FallBack betűtípusok listájához.

--------------------

> ```
> //Új példányt hoz létre a FontFallBackRule-ból
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //A szabályhoz három további betűtípust ad 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontNames | java.lang.String[] | A betűtípus neve vagy nevei (vesszővel elválasztva) a FallBack számára |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

A folyamatos Unicode-tartomány első indexét adja vissza.

**Visszatérési érték:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

A folyamatos Unicode-tartomány első indexét adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

A folyamatos Unicode-tartomány utolsó indexét adja vissza.

**Visszatérési érték:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

A folyamatos Unicode-tartomány utolsó indexét adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

A tartományhoz ténylegesen definiált betűtípusok számát adja vissza. Csak olvasható int.

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

A megadott indexű betűtípus nevét adja vissza. Csak olvasható [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

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

Eltávolítja az összes betűtípust a listáról.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Eltávolítja egy adott FallBack betűtípus első előfordulását a listáról.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Eltávolítja a Tahoma betűtípust a listáról.
>  newRule.remove("Tahoma");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A listáról eltávolítandó betűtípus neve. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a FallBack betűtípust a lista megadott indexén.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //A Tahoma betűtípust eltávolítja a listáról.
>  newRule.remove(2);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A betűtípus eltávolításához használt nulla-alapú index. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal ehhez a szabályhoz.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Lekéri az összes betűtípus nevét tömbként.
>  String[] fontNames = newRule.toArray();
> ```

**Visszatérési érték:**
java.lang.String[] - String tömb
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal a listában a megadott tartományból.

```
// Létrehoz egy szabályt, amely betűtípusok listáját tartalmazza.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Lekéri az utolsó két betűtípus nevét tömbként.
 String[] fontNames = newRule.toArray(2, 2);
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első hozzáadandó betűtípus indexe. |
| count | int | A hozzáadandó betűtípusok száma. |

**Visszatérési érték:**
java.lang.String[] - String tömb
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

Visszaadja a megadott szabály indexét a gyűjteményben.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmaz.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincio, MS Gothic, Tahoma, Times New Roman");
>  // Lekéri a Tahoma indexét.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A keresendő betűtípus neve. |

**Visszatérési érték:**
int - A betűtípus indexe vagy -1, ha a betűtípus nem található a listában.