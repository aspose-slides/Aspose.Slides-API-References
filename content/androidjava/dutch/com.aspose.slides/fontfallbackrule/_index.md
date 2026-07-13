---
title: FontFallBackRule
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een font fallback-regel voor
type: docs
url: /nl/com.aspose.slides/fontfallbackrule/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Stelt een font fallback-regel voor
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Creëert een nieuw exemplaar. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Creëert een nieuw exemplaar. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Voegt nieuwe lettertypen toe aan de lijst met FallBack-lettertypen. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Retourneert de eerste index van een doorlopend Unicode-bereik. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Retourneert de eerste index van een doorlopend Unicode-bereik. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Retourneert de laatste index van een doorlopend Unicode-bereik. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Retourneert de laatste index van een doorlopend Unicode-bereik. |
| [getCount()](#getCount--) | Haalt het aantal lettertypen op dat daadwerkelijk voor het bereik is gedefinieerd. |
| [get_Item(int index)](#get-Item-int-) | Haalt de lettertype-naam op op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle lettertypen uit de lijst. |
| [remove(String fontName)](#remove-java.lang.String-) | Verwijdert de eerste voorkoming van een specifiek FallBack-lettertype uit de lijst. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het FallBack-lettertype op de opgegeven index van de lijst. |
| [toArray()](#toArray--) | Creëert en retourneert een array met alle FallBack-lettertypen voor deze regel. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creëert en retourneert een array met alle FallBack-lettertypen uit het gespecificeerde bereik in de lijst. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Retourneert een index van de gespecificeerde regel in de collectie. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

Creëert een nieuw exemplaar.

--------------------

> ```
> // Maak een nieuw exemplaar van FantFallBackRule met één lettertype.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Maak een nieuw exemplaar van FantFallBackRule met meerdere lettertypen.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | long | Start-index van unicode-bereik |
| endIndex | long | Eind-index van unicode-bereik |
| fontNames | java.lang.String | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Creëert een nieuw exemplaar.

--------------------

> ```
> // Maak een nieuw exemplaar van FantFallBackRule met twee lettertypen
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Maak een nieuw exemplaar van FantFallBackRule met meerdere lettertypen.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | long | Start-index van unicode-bereik |
| endIndex | long | Eind-index van unicode-bereik |
| fontNames | java.lang.String[] | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen.

--------------------

> ```
> // Maak een nieuw exemplaar van FontFallBackRule
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
public final void addFallBackFonts(String[] fontNames)
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
public final long getRangeStartIndex()
```

Retourneert de eerste index van een doorlopend Unicode-bereik.

**Retourneert:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

Retourneert de eerste index van een doorlopend Unicode-bereik.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

Retourneert de laatste index van een doorlopend Unicode-bereik.

**Retourneert:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

Retourneert de laatste index van een doorlopend Unicode-bereik.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

Haalt het aantal lettertypen op dat daadwerkelijk voor het bereik is gedefinieerd. Alleen-lezen int.

**Retourneert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

Haalt de lettertype-naam op op de opgegeven index. Alleen-lezen [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle lettertypen uit de lijst.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Verwijdert de eerste voorkoming van een specifiek FallBack-lettertype uit de lijst.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Verwijder Tahoma uit de lijst.
>  newRule.remove("Tahoma");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | De naam van het te verwijderen lettertype uit de lijst. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het FallBack-lettertype op de opgegeven index van de lijst.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Verwijdert Tahoma uit de lijst.
>  newRule.remove(2);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen lettertype. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

Creëert en retourneert een array met alle FallBack-lettertypen voor deze regel.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Haal alle lettertypen op als array.
>  String[] fontNames = newRule.toArray();
> ```


**Retourneert:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Creëert en retourneert een array met alle FallBack-lettertypen uit het gespecificeerde bereik in de lijst.

```
// Maak een regel die een lijst met lettertypen bevat.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Haal de laatste twee lettertype-namen op als array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Een index van het eerste toe te voegen lettertype. |
| count | int | Een aantal toe te voegen lettertypen. |

**Retourneert:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

Retourneert een index van de gespecificeerde regel in de collectie.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Haal de index van Tahoma op.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Naam van het te zoeken lettertype. |

**Retourneert:**
int - Index van een lettertype of -1 als het lettertype niet in de lijst is gevonden.