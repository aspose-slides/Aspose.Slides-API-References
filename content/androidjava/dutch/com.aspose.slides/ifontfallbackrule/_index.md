---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een fontfallbackregel voor
type: docs
url: /nl/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Stelt een fontfallbackregel voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Haal de eerste index van een doorlopende Unicode-reeks op. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Haal de laatste index van een doorlopende Unicode-reeks op. |
| [getCount()](#getCount--) | Haalt het aantal lettertypen op dat daadwerkelijk voor het bereik is gedefinieerd. |
| [get_Item(int index)](#get-Item-int-) | Haalt de lettertype-naam op op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle lettertypen uit de lijst. |
| [remove(String fontName)](#remove-java.lang.String-) | Verwijdert het eerste voorkomen van een specifiek FallBack-lettertype uit de lijst. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het FallBack-lettertype op de opgegeven index in de lijst. |
| [toArray()](#toArray--) | Maakt en retourneert een array met alle FallBack-lettertypen voor deze regel. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt en retourneert een array met alle FallBack-lettertypen uit het opgegeven bereik in de lijst. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Retourneert een index van de opgegeven regel in de collectie. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen.

--------------------

> ```
> //Maak een nieuwe instantie van FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Voeg een tweede lettertype toe aan de regel 
>  newRule.addFallBackFonts("MS Gothic");
>  //Voeg een derde en vierde lettertype toe aan de regel 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen.

--------------------

> ```
> //Maak een nieuwe instantie van FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Voeg nog drie lettertypen toe aan de regel 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Haal de eerste index van een doorlopende Unicode-reeks op.

**Retour:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Haal de laatste index van een doorlopende Unicode-reeks op.

**Retour:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het aantal lettertypen op dat daadwerkelijk voor het bereik is gedefinieerd.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Haalt de lettertype-naam op op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour:**
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

Verwijdert het eerste voorkomen van een specifiek FallBack-lettertype uit de lijst.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Verwijderen van Tahoma uit de lijst
>  newRule.remove("Tahoma");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | De naam van het te verwijderen lettertype uit de lijst. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen lettertype. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Maakt en retourneert een array met alle FallBack-lettertypen voor deze regel.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Haalt alle letternamen op als array
>  String[] fontNames = newRule.toArray();
> ```


**Retour:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Maakt en retourneert een array met alle FallBack-lettertypen uit het opgegeven bereik in de lijst.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Haal de laatste twee lettertypen op als array
>  String[] fontNames = newRule.toArray(2,2);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Een index van het eerste toe te voegen lettertype. |
| count | int | Het aantal toe te voegen lettertypen. |

**Retour:**
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
>  //Haalt de index van Tahoma op
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Naam van het te zoeken lettertype. |

**Retour:**
int - Index of a font or -1 if font not found in list.