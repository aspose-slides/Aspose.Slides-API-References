---
title: IFontFallBackRule
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Representuje pravidlo náhradního písma
type: docs
url: /cs/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Representuje pravidlo náhradního písma
## Metody

| Metoda | Popis |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Přidá nové písmo (písma) do seznamu FallBack fonts. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Přidá nové písma do seznamu FallBack fonts. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Získá první index spojitého unicode rozsahu. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Získá poslední index spojitého unicode rozsahu. |
| [getCount()](#getCount--) | Získá počet písem skutečně definovaných pro rozsah. |
| [get_Item(int index)](#get-Item-int-) | Získá název písma na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechna písma ze seznamu. |
| [remove(String fontName)](#remove-java.lang.String-) | Odstraní první výskyt konkrétního FallBack fontu ze seznamu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní FallBack font na zadaném indexu seznamu. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole se všemi FallBack fonty pro toto pravidlo. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Vytvoří a vrátí pole se všemi FallBack fonty ze zadaného rozsahu v seznamu. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Vrací index zadaného pravidla ve sbírce. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


Přidá nové písmo (písma) do seznamu FallBack fonts.

--------------------

> ```
> //Vytvoří novou instanci FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Přidá druhé písmo do pravidla 
>  newRule.addFallBackFonts("MS Gothic");
>  //Přidá třetí a čtvrté písmo do pravidla 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | java.lang.String | Název písma nebo názvy (oddělené čárkou) pro FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```


Přidá nové písma do seznamu FallBack fonts.

--------------------

> ```
> //Vytvoří novou instanci FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Přidá další tři písma do pravidla 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontNames | java.lang.String[] | Název písma nebo názvy (oddělené čárkou) pro FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```


Získá první index spojitého unicode rozsahu.

**Vrací:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```


Získá poslední index spojitého unicode rozsahu.

**Vrací:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```


Získá počet písem skutečně definovaných pro rozsah.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```


Získá název písma na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechna písma ze seznamu.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```


Odstraní první výskyt konkrétního FallBack fontu ze seznamu.

--------------------

> ```
> // Vytvoří pravidlo obsahující seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Odstranění Tahoma ze seznamu
>  newRule.remove("Tahoma");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | java.lang.String | Název písma, který má být odstraněn ze seznamu. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní FallBack font na zadaném indexu seznamu.

--------------------

> ```
> // Vytvoří pravidlo obsahující seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Odstranění Tahoma ze seznamu
>  newRule.remove(2);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index písma (od nuly), které má být odstraněno. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```


Vytvoří a vrátí pole se všemi FallBack fonty pro toto pravidlo.

--------------------

> ```
> // Vytvoří pravidlo obsahující seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Získá všechny názvy písem jako pole
>  String[] fontNames = newRule.toArray();
> ```


**Vrací:**
java.lang.String[] - Pole řetězců
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


Vytvoří a vrátí pole se všemi FallBack fonty ze zadaného rozsahu v seznamu.

--------------------

> ```
> // Vytvoří pravidlo obsahující seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Získá poslední dvě názvy písem jako pole
>  String[] fontNames = newRule.toArray(2,2);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Index prvního písma, které se má přidat. |
| count | int | Počet písem, které se mají přidat. |

**Vrací:**
java.lang.String[] - Pole řetězců
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```


Vrací index zadaného pravidla ve sbírce.

--------------------

> ```
> // Vytvoří pravidlo obsahující seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Získá index Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | java.lang.String | Název písma k vyhledání. |

**Vrací:**
int - Index písma nebo -1, pokud písmo v seznamu není nalezeno.