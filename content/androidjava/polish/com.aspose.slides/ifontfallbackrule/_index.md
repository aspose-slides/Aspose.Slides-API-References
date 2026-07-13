---
title: IFontFallBackRule
second_title: Aspose.Slides for Android – odwołanie do API w Javie
description: Reprezentuje regułę zastępowania czcionek
type: docs
url: /pl/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Reprezentuje regułę zastępowania czcionek
## Metody

| Metoda | Opis |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Dodaje nowe czcionki do listy czcionek FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Dodaje nowe czcionki do listy czcionek FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Pobiera pierwszy indeks ciągłego zakresu Unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Pobiera ostatni indeks ciągłego zakresu Unicode. |
| [getCount()](#getCount--) | Zwraca liczbę czcionek rzeczywiście zdefiniowanych dla zakresu. |
| [get_Item(int index)](#get-Item-int-) | Zwraca nazwę czcionki podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie czcionki z listy. |
| [remove(String fontName)](#remove-java.lang.String-) | Usuwa pierwsze wystąpienie określonej czcionki FallBack z listy. |
| [removeAt(int index)](#removeAt-int-) | Usuwa czcionkę FallBack podanym indeksie na liście. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack dla tej reguły. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack z określonego zakresu na liście. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Zwraca indeks określonej reguły w kolekcji. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Dodaje nowe czcionki do listy czcionek FallBack.

--------------------

> ```
> //Utwórz nową instancję FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Dodaj drugą czcionkę do reguły 
>  newRule.addFallBackFonts("MS Gothic");
>  //Dodaj trzecią i czwartą czcionkę do reguły 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | java.lang.String | Nazwa czcionki lub nazwy (oddzielone przecinkiem) dla FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
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
| fontNames | java.lang.String[] | Nazwa czcionki lub nazwy (oddzielone przecinkiem) dla FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Pobiera pierwszy indeks ciągłego zakresu Unicode.

**Zwraca:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Pobiera ostatni indeks ciągłego zakresu Unicode.

**Zwraca:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Zwraca liczbę czcionek rzeczywiście zdefiniowanych dla zakresu.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Zwraca nazwę czcionki podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie czcionki z listy.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Usuwa pierwsze wystąpienie określonej czcionki FallBack z listy.

--------------------

> ```
> // Utwórz regułę zawierającą listę czcionek.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Usuwanie Tahoma z listy
>  newRule.remove("Tahoma");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | java.lang.String | Nazwa czcionki do usunięcia z listy. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa czcionkę FallBack podanym indeksie na liście.

--------------------

> ```
> // Utwórz regułę zawierającą listę czcionek.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Usuwanie Tahoma z listy
>  newRule.remove(2);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy czcionki do usunięcia. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack dla tej reguły.

--------------------

> ```
> //Utwórz regułę zawierającą listę czcionek.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Pobierz wszystkie nazwy czcionek jako tablicę
>  String[] fontNames = newRule.toArray();
> ```

**Zwraca:**
java.lang.String[] - Tablica ciągów
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Tworzy i zwraca tablicę ze wszystkimi czcionkami FallBack z określonego zakresu na liście.

--------------------

> ```
> // Utwórz regułę zawierającą listę czcionek.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Pobierz dwie ostatnie nazwy czcionek jako tablicę
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszej czcionki do dodania. |
| count | int | Liczba czcionek do dodania. |

**Zwraca:**
java.lang.String[] - Tablica ciągów
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Zwraca indeks określonej reguły w kolekcji.

--------------------

> ```
> // Utwórz regułę zawierającą listę czcionek.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Pobierz indeks Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | java.lang.String | Nazwa czcionki do znalezienia. |

**Zwraca:**
int - Indeks czcionki lub -1, jeśli czcionka nie została znaleziona na liście.