---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Referencia
description: Ábrázolja a betűtípus visszalépési szabályt
type: docs
url: /hu/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Ábrázolja a betűtípus visszalépési szabályt
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Új betűtípust vagy betűtípusokat ad a FallBack betűtípusok listájához. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Új betűtípusokat ad a FallBack betűtípusok listájához. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Az egymást követő Unicode-tartomány első indexét adja vissza. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Az egymást követő Unicode-tartomány utolsó indexét adja vissza. |
| [getCount()](#getCount--) | Visszaadja a tartományhoz ténylegesen definiált betűtípusok számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexhez tartozó betűtípus nevét. |
| [clear()](#clear--) | Eltávolítja az összes betűtípust a listáról. |
| [remove(String fontName)](#remove-java.lang.String-) | Eltávolítja a listáról egy adott FallBack betűtípus első előfordulását. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a listán a megadott indexű FallBack betűtípust. |
| [toArray()](#toArray--) | Létrehozza és visszaadja az összes FallBack betűtípust tartalmazó tömböt ehhez a szabályhoz. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehozza és visszaadja a megadott tartományból származó összes FallBack betűtípust tartalmazó tömböt a listában. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Visszaadja a megadott szabály indexét a gyűjteményben. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Új betűtípust vagy betűtípusokat ad a FallBack betűtípusok listájához.

--------------------

> ```
> //Új példány létrehozása a FantFallBackRule számára
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Második betűtípust ad hozzá a szabályhoz 
>  newRule.addFallBackFonts("MS Gothic");
>  //Harmadik és negyedik betűtípusokat ad hozzá a szabályhoz 
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
>  //Hozzáad három további betűtípust a szabályhoz 
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

Az egymást követő Unicode-tartomány első indexét adja vissza.

**Visszatér:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Az egymást követő Unicode-tartomány utolsó indexét adja vissza.

**Visszatér:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja a tartományhoz ténylegesen definiált betűtípusok számát.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Visszaadja a megadott indexhez tartozó betűtípus nevét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
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

Eltávolítja a listáról egy adott FallBack betűtípus első előfordulását.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma eltávolítása a listáról
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

Eltávolítja a listán a megadott indexű FallBack betűtípust.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tahoma eltávolítása a listáról
>  newRule.remove(2);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó betűtípus nulláralapú indexe. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Létrehozza és visszaadja az összes FallBack betűtípust tartalmazó tömböt ehhez a szabályhoz.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmazza.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Az összes betűtípus nevet tömbként kapja meg
>  String[] fontNames = newRule.toArray();
> ```


**Visszatér:**
java.lang.String[] - String tömb
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Létrehozza és visszaadja a megadott tartományból származó összes FallBack betűtípust tartalmazó tömböt a listában.

--------------------

> ```
> // Létrehoz egy szabályt, amely betűtípusok listáját tartalmaz.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Az utolsó két betűtípus nevet tömbként kapja meg
>  String[] fontNames = newRule.toArray(2,2);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első hozzáadandó betűtípus indexe. |
| count | int | A hozzáadandó betűtípusok száma. |

**Visszatér:**
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
>  //A Tahoma indexének lekérése
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | A keresendő betűtípus neve. |

**Visszatér:**
int - A betűtípus indexe, vagy -1, ha a betűtípus nem található a listában.