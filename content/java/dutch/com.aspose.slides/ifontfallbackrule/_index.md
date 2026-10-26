---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: Stelt een font fallback regel voor
type: docs
url: /nl/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Stelt een font fallback regel voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Voegt nieuwe lettertypen toe aan de lijst met FallBack-lettertypen. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Haalt de eerste index op van een doorlopend Unicode-bereik. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Haalt de laatste index op van een doorlopend Unicode-bereik. |
| [getCount()](#getCount--) | Haalt het aantal lettertypen op dat daadwerkelijk voor het bereik is gedefinieerd. |
| [get_Item(int index)](#get-Item-int-) | Haalt de naam van het lettertype op op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle lettertypen uit de lijst. |
| [remove(String fontName)](#remove-java.lang.String-) | Verwijdert de eerste voorkomen van een specifiek FallBack-lettertype uit de lijst. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het FallBack-lettertype op de opgegeven index in de lijst. |
| [toArray()](#toArray--) | Maakt een array met alle FallBack-lettertypen voor deze regel en retourneert deze. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt een array met alle FallBack-lettertypen uit het opgegeven bereik in de lijst en retourneert deze. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Retourneert een index van de opgegeven regel in de collectie. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen.

--------------------

> ```
> //Maak een nieuw exemplaar van FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Voeg een tweede lettertype toe aan de regel 
>  newRule.addFallBackFonts("MS Gothic");
>  //Voeg een derde en vierde lettertype toe aan de regel 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Voegt nieuwe lettertypen toe aan de lijst met FallBack-lettertypen.

--------------------

> ```
> //Maak een nieuw exemplaar van FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Voeg nog drie lettertypen toe aan de regel 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontNames | java.lang.String[] | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Haalt de eerste index op van een doorlopend Unicode-bereik.

**Returns:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Haalt de laatste index op van een doorlopend Unicode-bereik.

**Returns:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het aantal lettertypen op dat daadwerkelijk voor het bereik is gedefinieerd.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Haalt de naam van het lettertype op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Returns:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle lettertypen uit de lijst.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Verwijdert de eerste voorkomen van een specifiek FallBack-lettertype uit de lijst.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Verwijderen van Tahoma uit de lijst
>  newRule.remove("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | De naam van het lettertype dat uit de lijst moet worden verwijderd. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het FallBack-lettertype op de opgegeven index in de lijst.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Verwijderen van Tahoma uit de lijst
>  newRule.remove(2);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen lettertype. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Maakt een array met alle FallBack-lettertypen voor deze regel en retourneert deze.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Haal alle lettertype-namen op als array
>  String[] fontNames = newRule.toArray();
> ```

**Returns:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Maakt een array met alle FallBack-lettertypen uit het opgegeven bereik in de lijst en retourneert deze.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Haal de laatste twee lettertype-namen op als array
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Een index van het eerste toe te voegen lettertype. |
| count | int | Een aantal toe te voegen lettertypen. |

**Returns:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Retourneert een index van de opgegeven regel in de collectie.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Haal index van Tahoma op
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Naam van het te vinden lettertype. |

**Returns:**
int - Index van een lettertype of -1 als het lettertype niet in de lijst voorkomt.