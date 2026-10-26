---
title: FontFallBackRule
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar fontfallback-regel
type: docs
url: /sv/com.aspose.slides/fontfallbackrule/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Representerar regel för fontfallback
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Skapar en ny instans. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Skapar en ny instans. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Lägger till nya teckensnitt till listan med FallBack-teckensnitt. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Lägger till nya teckensnitt till listan med FallBack-teckensnitt. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Hämtar första indexet för ett kontinuerligt Unicode-område. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Hämtar första indexet för ett kontinuerligt Unicode-område. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Hämtar sista indexet för ett kontinuerligt Unicode-område. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Hämtar sista indexet för ett kontinuerligt Unicode-område. |
| [getCount()](#getCount--) | Hämtar antalet teckensnitt som faktiskt definierats för intervallet. |
| [get_Item(int index)](#get-Item-int-) | Hämtar teckensnittets namn på angivet index. |
| [clear()](#clear--) | Tar bort alla teckensnitt från listan. |
| [remove(String fontName)](#remove-java.lang.String-) | Tar bort den första förekomsten av ett specifikt FallBack-teckensnitt från listan. |
| [removeAt(int index)](#removeAt-int-) | Tar bort FallBack-teckensnittet på angivet index i listan. |
| [toArray()](#toArray--) | Skapar och returnerar en array med alla FallBack-teckensnitt för denna regel. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Skapar och returnerar en array med alla FallBack-teckensnitt från det angivna intervallet i listan. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Returnerar ett index för den angivna regeln i samlingen. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

Skapar en ny instans.

--------------------

> ```
> // Skapa ny instans av FantFallBackRule med ett teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Skapa ny instans av FantFallBackRule med flera teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | long | Startindex för Unicode-intervallet |
| endIndex | long | Slutindex för Unicode-intervallet |
| fontNames | java.lang.String | Teckensnittets namn eller namn (avgränsade med kommatecken) för FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Skapar en ny instans.

--------------------

> ```
> // Skapa ny instans av FantFallBackRule med två teckensnitt
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Skapa ny instans av FantFallBackRule med flera teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | long | Startindex för Unicode-intervallet |
| endIndex | long | Slutindex för Unicode-intervallet |
| fontNames | java.lang.String[] | Teckensnittets namn eller namn (avgränsade med kommatecken) för FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Lägger till nya teckensnitt till listan med FallBack-teckensnitt.

--------------------

> ```
> // Skapa ny instans av FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Lägg till ett andra teckensnitt till regeln 
>  newRule.addFallBackFonts("MS Gothic");
>  //Lägg till ett tredje och fjärde teckensnitt till regeln 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Teckensnittets namn eller namn (avgränsade med kommatecken) för FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

Lägger till nya teckensnitt till listan med FallBack-teckensnitt.

--------------------

> ```
> //Skapa ny instans av FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Lägg till ytterligare tre teckensnitt till regeln 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontNames | java.lang.String[] | Teckensnittets namn eller namn (avgränsade med kommatecken) för FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

Hämtar första indexet för ett kontinuerligt Unicode-område.

**Returnerar:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

Hämtar första indexet för ett kontinuerligt Unicode-område.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

Hämtar sista indexet för ett kontinuerligt Unicode-område.

**Returnerar:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

Hämtar sista indexet för ett kontinuerligt Unicode-område.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

Hämtar antalet teckensnitt som faktiskt definierats för intervallet. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

Hämtar teckensnittets namn på angivet index. Skrivskyddad [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

Tar bort alla teckensnitt från listan.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Tar bort den första förekomsten av ett specifikt FallBack-teckensnitt från listan.

--------------------

> ```
> // Skapa en regel som innehåller en lista med teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Ta bort Tahoma från listan.
>  newRule.remove("Tahoma");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Teckensnittets namn som ska tas bort från listan. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort FallBack-teckensnittet på angivet index i listan.

--------------------

> ```
> // Skapa en regel som innehåller en lista med teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tar bort Tahoma från listan.
>  newRule.remove(2);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index för teckensnittet som ska tas bort. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

Skapar och returnerar en array med alla FallBack-teckensnitt för denna regel.

--------------------

> ```
> // Skapa en regel som innehåller en lista med teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Hämta alla teckensnittsnamn som en array.
>  String[] fontNames = newRule.toArray();
> ```

**Returnerar:**
java.lang.String[] - Array av String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Skapar och returnerar en array med alla FallBack-teckensnitt från det angivna intervallet i listan.

```
// Skapa en regel som innehåller en lista med teckensnitt.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Hämta de två sista teckensnittsnamnen som en array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Index för det första teckensnittet att lägga till. |
| count | int | Antalet teckensnitt att lägga till. |

**Returnerar:**
java.lang.String[] - Array av String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

Returnerar ett index för den angivna regeln i samlingen.

--------------------

> ```
> // Skapa en regel som innehåller en lista med teckensnitt.
>  // Hämta index för Tahoma.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Teckensnittets namn att söka efter. |

**Returnerar:**
int - Index för ett teckensnitt eller -1 om teckensnittet ej finns i listan.