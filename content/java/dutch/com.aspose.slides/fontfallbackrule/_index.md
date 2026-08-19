---
title: FontFallBackRule
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een lettertype fallback-regel
type: docs
url: /nl/com.aspose.slides/fontfallbackrule/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Representeert lettertype fallback-regel
## Constructors

| Constructor | Description |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Maakt een nieuw exemplaar. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Maakt een nieuw exemplaar. |
## Methods

| Method | Description |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Voegt een nieuw lettertype toe aan de lijst met FallBack-lettertypen. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Voegt nieuwe lettertypen toe aan de lijst met FallBack-lettertypen. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Haalt de eerste index van een doorlopend Unicode-bereik op. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Haalt de eerste index van een doorlopend Unicode-bereik op. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Haalt de laatste index van een doorlopend Unicode-bereik op. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Haalt de laatste index van een doorlopend Unicode-bereik op. |
| [getCount()](#getCount--) | Haalt het aantal lettertypen op dat daadwerkelijk voor het bereik is gedefinieerd. |
| [get_Item(int index)](#get-Item-int-) | Haalt de naam van het lettertype op op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle lettertypen uit de lijst. |
| [remove(String fontName)](#remove-java.lang.String-) | Verwijdert het eerste voorkomen van een specifiek FallBack-lettertype uit de lijst. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het FallBack-lettertype op de opgegeven index in de lijst. |
| [toArray()](#toArray--) | Maakt een array met alle FallBack-lettertypen voor deze regel en retourneert deze. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt een array met alle FallBack-lettertypen uit het opgegeven bereik in de lijst en retourneert deze. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Retourneert de index van de opgegeven regel in de collectie. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Maakt een nieuw exemplaar.

--------------------

> ```
> // Maak een nieuw exemplaar van FantFallBackRule met één lettertype.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Maak een nieuw exemplaar van FantFallBackRule met meerdere lettertypen.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | long | Start-index van Unicode-bereik |
| endIndex | long | Eind-index van Unicode-bereik |
| fontNames | java.lang.String | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Maakt een nieuw exemplaar.

--------------------

> ```
> // Maak een nieuw exemplaar van FantFallBackRule met twee lettertypen
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Maak een nieuw exemplaar van FantFallBackRule met meerdere lettertypen.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | long | Start-index van Unicode-bereik |
| endIndex | long | Eind-index van Unicode-bereik |
| fontNames | java.lang.String[] | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Voegt een nieuw lettertype toe aan de lijst met FallBack-lettertypen.

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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Haalt de eerste index van een doorlopend Unicode-bereik op.

**Returns:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Haalt de eerste index van een doorlopend Unicode-bereik op.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Haalt de laatste index van een doorlopend Unicode-bereik op.

**Returns:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Haalt de laatste index van een doorlopend Unicode-bereik op.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Haalt het aantal lettertypen op dat daadwerkelijk voor het bereik is gedefinieerd. Alleen-lezen int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Haalt de naam van het lettertype op op de opgegeven index. Alleen-lezen [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
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


Verwijdert het eerste voorkomen van een specifiek FallBack-lettertype uit de lijst.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Verwijder Tahoma uit de lijst.
>  newRule.remove("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | De te verwijderen lettertype-naam uit de lijst. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert het FallBack-lettertype op de opgegeven index in de lijst.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Verwijdert Tahoma uit de lijst.
>  newRule.remove(2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen lettertype. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Maakt een array met alle FallBack-lettertypen voor deze regel en retourneert deze.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Haal alle lettertypen op als array.
>  String[] fontNames = newRule.toArray();
> ```

**Returns:**
java.lang.String[] - Array van String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Maakt een array met alle FallBack-lettertypen uit het opgegeven bereik in de lijst en retourneert deze.

```
// Maak een regel die een lijst met lettertypen bevat.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Haal de laatste twee lettertypen op als array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Index van het eerste toe te voegen lettertype. |
| count | int | Aantal toe te voegen lettertypen. |

**Returns:**
java.lang.String[] - Array van String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Retourneert de index van de opgegeven regel in de collectie.

--------------------

> ```
> // Maak een regel die een lijst met lettertypen bevat.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Haal de index van Tahoma op.
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Naam van het te vinden lettertype. |

**Returns:**
int - Index van een lettertype of -1 als het lettertype niet in de lijst voorkomt.