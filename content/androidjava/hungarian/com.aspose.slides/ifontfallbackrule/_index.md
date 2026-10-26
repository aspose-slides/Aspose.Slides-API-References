---
title: IFontFallBackRule
second_title: Aspose.Slides Androidhoz Java API hivatkozással
description: A betűtípus visszaeső szabályt képviseli
type: docs
url: /hu/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

A betűtípus visszaeső szabályt képviseli
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Új betűtípust (betűtípusokat) ad a FallBack betűtípusok listájához. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Új betűtípusokat ad a FallBack betűtípusok listájához. |
| [getRangeStartIndex()](#getRangeStartIndex--) | A folyamatos Unicode tartomány első indexét adja vissza. |
| [getRangeEndIndex()](#getRangeEndIndex--) | A folyamatos Unicode tartomány utolsó indexét adja vissza. |
| [getCount()](#getCount--) | A tartományban ténylegesen definiált betűtípusok számát adja vissza. |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű betűtípus nevét adja vissza. |
| [clear()](#clear--) | Eltávolítja az összes betűtípust a listáról. |
| [remove(String fontName)](#remove-java.lang.String-) | Eltávolítja a megadott FallBack betűtípus első előfordulását a listáról. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a FallBack betűtípust a lista megadott indexén. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal ehhez a szabályhoz. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal a listában a megadott tartományból. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Visszaadja a megadott szabály indexét a gyűjteményben. |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Új betűtípust (betűtípusokat) ad a FallBack betűtípusok listájához.

--------------------

> ```
> //Új példány létrehozása a FantFallBackRule számára
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Második betűtípust ad a szabályhoz 
>  newRule.addFallBackFonts("MS Gothic");
>  //Harmadik és negyedik betűtípusok hozzáadása a szabályhoz 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A betűtípus neve vagy nevei (vesszővel elválasztva) a FallBack-hez |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Új betűtípusokat ad a FallBack betűtípusok listájához.

--------------------

> ```
> //Új példány létrehozása a FontFallBackRule számára
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //További három betűtípus hozzáadása a szabályhoz 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontNames | java.lang.String[] | A betűtípus neve vagy nevei (vesszővel elválasztva) a FallBack-hez |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

A folyamatos Unicode tartomány első indexét adja vissza.

**Visszatérési érték:**  
long

### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

A folyamatos Unicode tartomány utolsó indexét adja vissza.

**Visszatérési érték:**  
long

### getCount() {#getCount--}
```
public abstract int getCount()
```

A tartományban ténylegesen definiált betűtípusok számát adja vissza.

**Visszatérési érték:**  
int

### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

A megadott indexű betűtípus nevét adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**  
java.lang.String

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes betűtípust a listáról.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Eltávolítja a megadott FallBack betűtípus első előfordulását a listáról.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmaz.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma eltávolítása a listából
>  newRule.remove("Tahoma");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A listáról eltávolítandó betűtípus neve. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a FallBack betűtípust a lista megadott indexén.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmaz.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma eltávolítása a listából
>  newRule.remove(2);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A betűtípus eltávolításához használt nullától induló index. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal ehhez a szabályhoz.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmaz.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Az összes betűtípus nevet tömbként lekéri
>  String[] fontNames = newRule.toArray();
> ```

**Visszatérési érték:**  
java.lang.String[] - String tömb

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal a listában a megadott tartományból.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmaz.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Az utolsó két betűtípus nevet tömbként lekéri
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első hozzáadandó betűtípus indexe. |
| count | int | A hozzáadandó betűtípusok száma. |

**Visszatérési érték:**  
java.lang.String[] - String tömb

### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Visszaadja a megadott szabály indexét a gyűjteményben.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmaz.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tahoma indexének lekérése
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A keresendő betűtípus neve. |

**Visszatérési érték:**  
int - A betűtípus indexe, vagy -1 ha a betűtípus nem található a listában.