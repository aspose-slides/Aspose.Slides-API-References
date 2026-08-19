---
title: FontFallBackRule
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje pravidlo náhradního písma
type: docs
url: /cs/com.aspose.slides/fontfallbackrule/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Reprezentuje pravidlo záložního písma
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Vytvoří novou instanci. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Vytvoří novou instanci. |
## Metody

| Metoda | Popis |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Přidá nové písmo/písma do seznamu záložních fontů. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Přidá nová písma do seznamu záložních fontů. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Získá první index souvislého rozsahu Unicode. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Získá první index souvislého rozsahu Unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Získá poslední index souvislého rozsahu Unicode. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Získá poslední index souvislého rozsahu Unicode. |
| [getCount()](#getCount--) | Získá počet fontů skutečně definovaných pro rozsah. |
| [get_Item(int index)](#get-Item-int-) | Získá název fontu na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechna písma ze seznamu. |
| [remove(String fontName)](#remove-java.lang.String-) | Odstraní první výskyt konkrétního záložního fontu ze seznamu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní záložní font na zadaném indexu ze seznamu. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole se všemi záložními fonty pro toto pravidlo. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Vytvoří a vrátí pole se všemi záložními fonty ze zadaného rozsahu v seznamu. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Vrátí index zadaného pravidla ve sbírce. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Vytvoří novou instanci.

--------------------

> ```
> // Vytvořte novou instanci FantFallBackRule s jedním písmem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Vytvořte novou instanci FantFallBackRule s několika písmy.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | long | Počáteční index unicode rozsahu |
| endIndex | long | Koncový index unicode rozsahu |
| fontNames | java.lang.String | Název nebo názvy fontu (oddělené čárkou) pro záložní fonty |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Vytvoří novou instanci.

--------------------

> ```
> // Vytvořte novou instanci FantFallBackRule se dvěma písmy
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Vytvořte novou instanci FantFallBackRule s několika písmy.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | long | Počáteční index unicode rozsahu |
| endIndex | long | Koncový index unicode rozsahu |
| fontNames | java.lang.String[] | Název nebo názvy fontu (oddělené čárkou) pro záložní fonty |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Přidá nové písmo/písma do seznamu záložních fontů.

--------------------

> ```
> // Vytvořte novou instanci FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Přidejte druhé písmo k pravidlu 
>  newRule.addFallBackFonts("MS Gothic");
>  //Přidejte třetí a čtvrté písmo k pravidlu 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | java.lang.String | Název nebo názvy fontu (oddělené čárkou) pro záložní fonty |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Přidá nová písma do seznamu záložních fontů.

--------------------

> ```
> //Vytvořte novou instanci FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Přidejte další tři písma k pravidlu 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontNames | java.lang.String[] | Název nebo názvy fontu (oddělené čárkou) pro záložní fonty |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Získá první index souvislého rozsahu Unicode.

**Vrací:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Získá první index souvislého rozsahu Unicode.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Získá poslední index souvislého rozsahu Unicode.

**Vrací:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Získá poslední index souvislého rozsahu Unicode.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Získá počet fontů skutečně definovaných pro rozsah. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Získá název fontu na zadaném indexu. Pouze pro čtení [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


Odstraní všechna písma ze seznamu.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Odstraní první výskyt konkrétního záložního fontu ze seznamu.

--------------------

> ```
> // Vytvořte pravidlo, které obsahuje seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Odstraňte Tahoma ze seznamu.
>  newRule.remove("Tahoma");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | java.lang.String | Název fontu, který se má odstranit ze seznamu. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní záložní font na zadaném indexu ze seznamu.

--------------------

> ```
> // Vytvořte pravidlo, které obsahuje seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Minjo, MS Gothic, Tahoma, Times New Roman");
>  //Odstraňte Tahoma ze seznamu.
>  newRule.remove(2);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index fontu, který se má odstranit. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Vytvoří a vrátí pole se všemi záložními fonty pro toto pravidlo.

--------------------

> ```
> // Vytvořte pravidlo, které obsahuje seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Získejte všechny názvy písem jako pole.
>  String[] fontNames = newRule.toArray();
> ```


**Vrací:**
java.lang.String[] - Pole řetězců
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Vytvoří a vrátí pole se všemi záložními fonty ze zadaného rozsahu v seznamu.

```
// Vytvořte pravidlo, které obsahuje seznam písem.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Získejte poslední dva názvy písem jako pole.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Index prvního fontu, který se má přidat. |
| count | int | Počet fontů, které se mají přidat. |

**Vrací:**
java.lang.String[] - Pole řetězců
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Vrátí index zadaného pravidla ve sbírce.

--------------------

> ```
> // Vytvořte pravidlo, které obsahuje seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Získejte index Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | java.lang.String | Název fontu k vyhledání. |

**Vrací:**
int - Index fontu nebo -1, pokud font v seznamu není nalezen.