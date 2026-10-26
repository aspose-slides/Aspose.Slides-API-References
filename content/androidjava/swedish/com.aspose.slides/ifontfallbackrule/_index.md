---
title: IFontFallBackRule
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar regel för teckensnittsfallback
type: docs
url: /sv/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Representerar regel för teckensnittsfallback
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Lägger till ett eller flera nya teckensnitt i listan med FallBack-teckensnitt. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Lägger till nya teckensnitt i listan med FallBack-teckensnitt. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Hämtar första indexet för ett kontinuerligt unicode-intervall. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Hämtar sista indexet för ett kontinuerligt unicode-intervall. |
| [getCount()](#getCount--) | Hämtar antalet teckensnitt som faktiskt definierats för intervallet. |
| [get_Item(int index)](#get-Item-int-) | Hämtar teckensnittets namn på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla teckensnitt från listan. |
| [remove(String fontName)](#remove-java.lang.String-) | Tar bort den första förekomsten av ett specifikt FallBack-teckensnitt från listan. |
| [removeAt(int index)](#removeAt-int-) | Tar bort FallBack-teckensnittet på det angivna indexet i listan. |
| [toArray()](#toArray--) | Skapar och returnerar en array med alla FallBack-teckensnitt för denna regel. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Skapar och returnerar en array med alla FallBack-teckensnitt från det angivna intervallet i listan. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Returnerar ett index för den angivna regeln i samlingen. |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Lägger till ett eller flera nya teckensnitt i listan med FallBack-teckensnitt.

--------------------

> ```
> //Skapa en ny instans av FantFallBackRule
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
public abstract void addFallBackFonts(String[] fontNames)
```

Lägger till nya teckensnitt i listan med FallBack-teckensnitt.

--------------------

> ```
> //Skapa en ny instans av FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Lägg till tre ytterligare teckensnitt till regeln 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontNames | java.lang.String[] | Teckensnittens namn eller namn (avgränsade med kommatecken) för FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Hämtar första indexet för ett kontinuerligt unicode-intervall.

**Returnerar:**
long

### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Hämtar sista indexet för ett kontinuerligt unicode-intervall.

**Returnerar:**
long

### getCount() {#getCount--}
```
public abstract int getCount()
```

Hämtar antalet teckensnitt som faktiskt definierats för intervallet.

**Returnerar:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Hämtar teckensnittets namn på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
java.lang.String

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla teckensnitt från listan.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Tar bort den första förekomsten av ett specifikt FallBack-teckensnitt från listan.

--------------------

> ```
> // Skapa en regel som innehåller en lista med teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tar bort Tahoma från listan
>  newRule.remove("Tahoma");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Teckensnittets namn som ska tas bort från listan. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort FallBack-teckensnittet på det angivna indexet i listan.

--------------------

> ```
> // Skapa en regel som innehåller en lista med teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tar bort Tahoma från listan
>  newRule.remove(2);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för teckensnittet som ska tas bort. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Skapar och returnerar en array med alla FallBack-teckensnitt för denna regel.

--------------------

> ```
> //Skapa en regel som innehåller en lista med teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Hämta alla font-namn som en array
>  String[] fontNames = newRule.toArray();
> ```


**Returnerar:**
java.lang.String[] - Array of String

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Skapar och returnerar en array med alla FallBack-teckensnitt från det angivna intervallet i listan.

--------------------

> ```
> // Skapa en regel som innehåller en lista med teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Hämta de två sista font-namnen som en array
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Ett index för det första teckensnittet att lägga till. |
| count | int | Ett antal teckensnitt att lägga till. |

**Returnerar:**
java.lang.String[] - Array of String

### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Returnerar ett index för den angivna regeln i samlingen.

--------------------

> ```
> // Skapa en regel som innehåller en lista med teckensnitt.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Hämta index för Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Teckensnittets namn att söka efter. |

**Returnerar:**
int - Index för ett teckensnitt eller -1 om teckensnittet inte finns i listan.