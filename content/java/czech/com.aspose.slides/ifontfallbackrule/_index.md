---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje pravidlo náhradního písma
type: docs
url: /cs/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Reprezentuje pravidlo náhradního písma
## Metody

| Metoda | Popis |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Adds a new font(s) to the list of FallBack fonts. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Adds a new fonts to the list of FallBack fonts. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Get first index of continuous unicode range. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Get last index of continuous unicode range. |
| [getCount()](#getCount--) | Gets the number of fonts actually defined for range. |
| [get_Item(int index)](#get-Item-int-) | Gets the font name at the specified index. |
| [clear()](#clear--) | Removes all fonts from the list. |
| [remove(String fontName)](#remove-java.lang.String-) | Removes the first occurrence of a specific FallBack font from the list. |
| [removeAt(int index)](#removeAt-int-) | Removes the FallBack font at the specified index of the list. |
| [toArray()](#toArray--) | Creates and returns an array with all FallBack fonts for this rule. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all FallBack fonts from the specified range in list. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Returns an index of the specified rule in the collection. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Přidá nové písmo (písma) do seznamu náhradních písem.

--------------------

> ```
> //Vytvoření nové instance FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Přidejte druhé písmo do pravidla 
>  newRule.addFallBackFonts("MS Gothic");
>  //Přidejte třetí a čtvrté písmo do pravidla 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font's name or names (delimited by comma) for FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Přidá nová písma do seznamu náhradních písem.

--------------------

> ```
> //Vytvoření nové instance FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Přidání dalších tří písem do pravidla 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Získá první index souvislého Unicode rozsahu.

**Návratová hodnota:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Získá poslední index souvislého Unicode rozsahu.

**Návratová hodnota:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Získá počet písem skutečně definovaných pro rozsah.

**Návratová hodnota:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Získá název písma na zadaném indexu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
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

Odstraní první výskyt konkrétního náhradního písma ze seznamu.

--------------------

> ```
> // Vytvoří pravidlo obsahující seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Odstranění Tahoma ze seznamu
>  newRule.remove("Tahoma");
```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | The font's name to remove from the list. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní náhradní písmo na zadaném indexu ze seznamu.

--------------------

> ```
> // Vytvoří pravidlo obsahující seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Odstranění Tahoma ze seznamu
>  newRule.remove(2);
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the font to remove. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Vytvoří a vrátí pole se všemi náhradními písmy pro toto pravidlo.

--------------------

> ```
> // Vytvoří pravidlo obsahující seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Získá všechny názvy písem jako pole
>  String[] fontNames = newRule.toArray();
> ```

**Návratová hodnota:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Vytvoří a vrátí pole se všemi náhradními písmy z určeného rozsahu v seznamu.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Get a last two font-names as array
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first font to add. |
| count | int | A number of fonts to add. |

**Návratová hodnota:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Vrací index daného pravidla ve sbírce.

--------------------

> ```
> // Vytvoří pravidlo obsahující seznam písem.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Získá index Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font's name to find. |

**Návratová hodnota:**
int - Index of a font or -1 if font not found in list.