---
title: FontFallBackRule
second_title: Referencja API Aspose.Slides dla Javy
description: Reprezentuje regułę zastępczą czcionki
type: docs
url: /pl/com.aspose.slides/fontfallbackrule/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Reprezentuje regułę zastępczą czcionki
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Tworzy nową instancję. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Tworzy nową instancję. |
## Metody

| Metoda | Opis |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Dodaje nowe czcionki do listy czcionek FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Dodaje nowe czcionki do listy czcionek FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Pobiera pierwszy indeks ciągłego zakresu unicode. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Pobiera pierwszy indeks ciągłego zakresu unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Pobiera ostatni indeks ciągłego zakresu unicode. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Pobiera ostatni indeks ciągłego zakresu unicode. |
| [getCount()](#getCount--) | Pobiera liczbę czcionek rzeczywiście zdefiniowanych dla zakresu. |
| [get_Item(int index)](#get-Item-int-) | Pobiera nazwę czcionki podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie czcionki z listy. |
| [remove(String fontName)](#remove-java.lang.String-) | Usuwa pierwsze wystąpienie określonej czcionki FallBack z listy. |
| [removeAt(int index)](#removeAt-int-) | Usuwa czcionkę FallBack pod wskazanym indeksem na liście. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack dla tej reguły. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack z określonego zakresu na liście. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Zwraca indeks określonej reguły w kolekcji. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

Tworzy nową instancję.

--------------------

> ```
> // Utwórz nową instancję FantFallBackRule z jedną czcionką.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Utwórz nową instancję FantFallBackRule z kilkoma czcionkami.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | long | Początkowy indeks zakresu unicode |
| endIndex | long | Końcowy indeks zakresu unicode |
| fontNames | java.lang.String | Nazwa lub nazwy czcionki (oddzielone przecinkiem) dla FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Tworzy nową instancję.

--------------------

> ```
> // Utwórz nową instancję FantFallBackRule z dwoma czcionkami
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Utwórz nową instancję FantFallBackRule z kilkoma czcionkami.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | long | Początkowy indeks zakresu unicode |
| endIndex | long | Końcowy indeks zakresu unicode |
| fontNames | java.lang.String[] | Nazwa lub nazwy czcionki (oddzielone przecinkiem) dla FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Dodaje nowe czcionki do listy czcionek FallBack.

--------------------

> ```
> // Utwórz nową instancję FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Dodaj drugą czcionkę do reguły 
>  newRule.addFallBackFonts("MS Gothic");
>  //Dodaj trzecią i czwartą czcionkę do reguły 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | java.lang.String | Nazwa lub nazwy czcionki (oddzielone przecinkiem) dla FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

Dodaje nowe czcionki do listy czcionek FallBack.

--------------------

> ```
> //Utwórz nową instancję FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Dodaj kolejne trzy czcionki do reguły 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nazwa lub nazwy czcionki (oddzielone przecinkiem) dla FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

Pobiera pierwszy indeks ciągłego zakresu unicode.

**Zwraca:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

Pobiera pierwszy indeks ciągłego zakresu unicode.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

Pobiera ostatni indeks ciągłego zakresu unicode.

**Zwraca:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

Pobiera ostatni indeks ciągłego zakresu unicode.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

Pobiera liczbę czcionek rzeczywiście zdefiniowanych dla zakresu. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

Pobiera nazwę czcionki podanym indeksie. Tylko do odczytu [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie czcionki z listy.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Usuwa pierwsze wystąpienie określonej czcionki FallBack z listy.

--------------------

> ```
> // Utwórz regułę zawierającą listę czcionek.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Usuń Tahoma z listy.
>  newRule.remove("Tahoma");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | java.lang.String | Nazwa czcionki do usunięcia z listy. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa czcionkę FallBack pod wskazanym indeksem na liście.

--------------------

> ```
> // Utwórz regułę zawierającą listę czcionek.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Usuwanie Tahoma z listy.
>  newRule.remove(2);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy czcionki do usunięcia. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack dla tej reguły.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Get all font names as array.
>  String[] fontNames = newRule.toArray();
> ```

**Zwraca:**
java.lang.String[] - Tablica ciągów
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack z określonego zakresu na liście.

```
// Utwórz regułę zawierającą listę czcionek.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Pobierz dwie ostatnie nazwy czcionek jako tablicę.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszej czcionki do dodania. |
| count | int | Liczba czcionek do dodania. |

**Zwraca:**
java.lang.String[] - Tablica ciągów
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

Zwraca indeks określonej reguły w kolekcji.

--------------------

> ```
> // Utwórz regułę zawierającą listę czcionek.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincio, MS Gothic, Tahoma, Times New Roman");
>  // Pobierz indeks Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | java.lang.String | Nazwa czcionki do znalezienia. |

**Zwraca:**
int - Indeks czcionki lub -1 jeśli czcionka nie została znaleziona na liście.